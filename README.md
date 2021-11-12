# Hand_Gesture_Recognition

# Introduction
Technology has driven us ahead to use only gestures to operate digital appliances, smart devices and other camera enabled devices rather than radio frequency signals. In this project we are developing system to use different hand gestures and detect each of them which may convey different message/ command/ instruction. 

Using advanced Data science, AI technique to create accurate models that predict the gestures which may be used in various applications that ease human interaction with machine effectively.  

# Business Problem
Our objective for this project is to build model that predicts hand gestures within a short span, irrespective of the distance(within camera visible range), skin color and any background

# About Data
The image dataset has 10 classes of gestures and of total 20k images. There are equal number of images for each class. Images will be of diferent persons, skin color and varied sizes, irrespective of the background. 
Data downloaded from kaggle: https://www.kaggle.com/gti-upm/leapgestrecog

Data is available in set of folders with near infrared images.


# Model summary
Model used is 8 layered CNN keras sequential model. 
Model summary: 2 Conv2D with Relu activation funtions, Flatten, 2 dropout layers, dense output layers with Softmax activation functions.

Libraries imported: Numpy, Matplotlib, tensorflow, keras, sklearn

# Results
Obtained an Accuracy of 99.77% on test data.
