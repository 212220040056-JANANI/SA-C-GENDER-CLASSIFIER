# SA-C-GENDER-CLASSIFIER
# Algorithm
1. To classify the gender of a person use the DeepFace library.
2. DeepFace library is developed based on deep learning algorithms.
3. Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements.
4. Load and display the imported image.
5. Pass the image to DeepFace library and analyze the image to predict gender of a person.
6. This prediction is stored in result variable.
7. Finally print the prediction using this algorithm.

## Program:
```
/*
Program to implement Gender Classification
Developed by   : Janani D
RegisterNumber : 212220040056

#install deepface
!pip install deepface

#import packages
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt

#read image
img1=cv2.imread('m10.jpg')

#show image
plt.imshow(img1[:,:,::-1])
plt.show()

#analyze gender
result=DeepFace.analyze(img1,actions=['gender'])
#print the gender
print("Gender : ",result['gender'])
*/
```

## OUTPUT:


![output](https://user-images.githubusercontent.com/86832944/173180684-73108abe-6298-40ea-b8f7-5974631db763.png)

 DEMO VIDEO YOUTUBE LINK:  https://youtu.be/vhvyhi5tzxk


