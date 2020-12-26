---
layout: single
title:  "Day 3: Facial Expression Recognition for Images and Videos with Keras"
header:
  teaser: "/posts_img/post3/result-express-recog.jpg"
categories: 
  - datascience
tags:
  - Data Science
  - Keras
  - Tensorflow
  - Flask
  - Convolutional Neural Networks
  - Deep Learning
---


This is part of the #DailyDataScience challenge. The challenge consists of an emersion into data and Data Science related projects.

For day 3, I worked on a project for facial expression recognition. I built and trained a convolutional neural network (CNN) in Keras to recognize facial expressions. The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). I used OpenCV to automatically detect faces in images and draw bounding boxes around them. Once the CNN model is trained, saved, and exported, it was served to a web interface to perform real-time facial expression recognition on video and image data. The work is part of a guided project on Coursera

The complete code could be found in my Github repository : 
[facial-expression-recognition-keras-and-tensorflow](https://github.com/adelzaitri/facial-expression-recognition-keras-and-tensorflow) 



Results
========

![Results for Facial Expression Recognition](/images/posts_img/post3/result-express-recog.jpg)


Goals:
======
* Develop a facial expression recognition model in Keras
* Build and train a convolutional neural network (CNN)
* Deploy the trained model to a web interface with Flask
* Apply the model to real-time video streams and image data

Project Steps:
======
1. Introduction and Overview
2. Explore the Dataset
3. Generate Training and Validation Batches
4. Create a Convolutional Neural Network (CNN) Model
5. Train and Evaluate Model
6. Save and Serialize Model as JSON String
7. Create a Flask App to Serve Predictions
8. Create a Class to Output Model Predictions
9. Design an HTML Template for the Flask App
10. Use Model to Recognize Facial Expressions in Videos

Data Sample:
=====

![Data Sample](/images/posts_img/post3/facial-express-data-example.png)

Convolutional Neural Network Model Details:
========
![CNN Model](/images/posts_img/post3/cnn.jpg)

Model Evaluation:
====
![accuracy of training and validation](/images/posts_img/post3/training-evaluation.jpg)

Data is available in:
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data 