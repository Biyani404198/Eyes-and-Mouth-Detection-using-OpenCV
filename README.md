# Eyes-and-Mouth-Detection-using-OpenCV
Eyes and Mouth Detection using Haar Cascades (OpenCV)

## Problem Statement:
Take a few facial images as inputs (from FFHQ dataset) The output has to be the coordinates of three bounding boxes - two maximally enclosing the eyes and one enclosing the mouth Your code should be in python. You can use PIL or openCV.

## Pre-trained Cascades used:
- haarcascade_eye.xml
- haarcascade_smile.xml

## Steps:
- Since it was my initial attempt at Haarcascading, I decided to start by working with a single image to gain a better understanding of how it functions.
- The initial cascading made no sense as there were multiple boxes at inappropriate positions. So I read the documentation for cv.CascadeClassifier.detectMultiScale() for better understanding.
- After getting an understanding of what each parameter does, I tried tuning them to see how it affects the cascading.
- After Cascading the image appropriately, I tried different image to verify the parameters, but it didn't cascade other picture appropriately. So I tried changing parameters a bit.
- I created a helper function to pick the maximum occuring value from the different value of scaleFactor.

![image](https://github.com/Biyani404198/Eyes-and-Mouth-Detection-using-OpenCV/assets/92304955/2b2b285e-e15c-42f9-b004-ab5e9049228f)

  
