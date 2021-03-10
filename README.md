# Facial-expression-recognition-and-emotion_analysis
Facial expression recognition using ensemble deep neural network
The three Deep Neural network is trained on the gray scale facial expression images.
It can be predict the 7 expressions in real time.--- ANGER , DISGUST , FEAR , HAPPY , SAD , NUTRAL , SURPRISE etc.
## Abstract
This  project aims to recognize facial expression  with CNN implemented by tensorflow and keras packages in python.  I also implement a real time module which  can real time capture image  user face through PC camera by using computer vision packages . computer vision library cropped the face it detects from the original frames and resize the cropped image to  48x48 grayscale  image, then take them as inputs of deep learning model. Moreover ,this  project also provides  a function which perform relation between two face expression. 
## Datasets
Why is Fer2013 dataset challenging?
The training set consists of 28,709 examples and  test set consists of 7178 examples. The images are not aligned and some of them are incorrectly labelled .After cleaning The training set consists of 16744 examples and  test set consists of 4144 examples.
Download Fer2013 dataset --https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

## custom network 
Ensemble CNN Deep 
1} network1 ,
2} network2 ,
3} network3
## Pre Trained network
DeepFace --DeepFace is a deep learning facial recognition system created by a research group at Facebook. 
## installation 
```
Keras ,
Tensorflow,
Opencv,
DeepFace .
```
# Testing on Real world Image
Steps are as follows :-
1. Read the image, convert it to gray-scaleimage for custom network or rgb image for deepface and save it.
2. Read that gray-scale saved image, then detect face in it using   HAAR cascade.
3. Crop the image to the detected face and resize it to 48*48 with one channel and save the image.
4. Read that processed cropped-resized image, then reshape it and normalize between(0,1) it.
5. Then feed that image Network  1,2, and 3   or deepface model.
6. Then use our own model (ensemble model ) for final prediction of expression.

# Use
understanding how these stuff work will enable you to explore & understand more interesting things build using them like the automatic FER (face expression recognation ) system.
Automatic detect customer satisfaction using smart camera.
Testing candidates during interviews.

[Linkedin post view](https://www.linkedin.com/posts/vishal-patil-b6a3a0195_successfully-completedproject-deeplearning-activity-6655350786471628800-qmVr)


### Test sample
![image](https://github.com/vishalbpatil1/Facial-expression-recognition-and-emotion_analysis/blob/master/face_exp3.png)
![image2](https://github.com/vishalbpatil1/Facial-expression-recognition-and-emotion_analysis/blob/master/face_exp2.png)
![image3](https://github.com/vishalbpatil1/Facial-expression-recognition-and-emotion_analysis/blob/master/face%20exp1.png)

