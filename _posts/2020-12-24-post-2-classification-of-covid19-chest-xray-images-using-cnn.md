---
layout: single
title:  "Day 2: Classification of COVID19 Chest X-ray Images using Convolutional Neural Network with Keras and Tensorflow"
header:
  teaser: "/posts_img/post2/sample_data.png"
categories: 
  - datascience
tags:
  - 66daysofdata
  - classification
  - Convolutional Neural Networks
  - TensorFlow
  - Deep Learning
  - Image Classifier

---
What
======
This is part of the #66daysofdata challenge. The challenge consists of an emersion into data and Data Science related projects throughout the next 66 days.

For day 2, I worked on creating a Convolutional Neural Network to classify X-ray images into COVID19 images or not.

The complete code could be found in my Github repository : 
[classification-of-covid19-using-chest-xray-images-in-keras](https://github.com/adelzaitri/classification-of-covid19-using-chest-xray-images-in-keras) 

Why
======
The objective of the work is educational, the goal is to practice creating a Convolutional Neural Network with Keras and Tensorflow.

* Predict whether a Chest X-ray is a COVID-19 diagnosis or not
* Build and Train the Convolutional Neural Network using Keras with Tensorflow as Backend
* Visualize Data in Matplotlib
* Make use of the Trained Model to Predict on a New Set of Data



Project Steps:
======
1. Introduction & Import Libraries
2. Clone and Explore Dataset 
3. Data Visualization
4. Data preprocessing and Augmentation
5. Build a Convolutional Neural Network (CNN)
6. Compile and Train the Model
7. Performance Evaluation
8. Prediction on New Data



Data Sample:
=====

![Data Sample](/images/posts_img/post2/sample_data.png)

Convolutional Neural Network Model Details:
========
![CNN Model](/images/posts_img/post2/model_details_cnn.jpg)

Model Evaluation:
====
* Accuracy on test data: 0.9752
* Accuracy during the training and validation: 

![accuracy of training and validation](/images/posts_img/post2/training_accuracy.png)