# SA-C-GENDER-CLASSIFIER
# Algorithm
1.To classify the gender of a person use the DeepFace library. <br>
2.DeepFace library is developed based on deep learning algorithms. <br>
3.Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements. <br>
4.Load and display the imported image. <br>
5.Pass the image to DeepFace library and analyze the image to predict gender of a person. <br>
6.This prediction is stored in result variable. <br>
7.Finally print the prediction using this algorithm. <br>


## Program:


# Program to implement 
## Developed by   :  PRASHETHAA R
## RegisterNumber :  212220230036



## Output:
```

1. CODE :
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('bj.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
img2=cv2.imread('jungkook.jpg')
plt.imshow(img2[:,:,::-1])
plt.show()
result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])

```
![image](https://user-images.githubusercontent.com/75234942/176353939-3e0ca3df-afb5-4375-b157-7d1ef4ec943f.png)

![image](https://user-images.githubusercontent.com/75234942/176354063-325039df-9f4a-4cfe-9c51-ded4f78d734f.png)

2. DEMO VIDEO YOUTUBE LINK:

https://youtu.be/1-WZr8_JtOE
 


