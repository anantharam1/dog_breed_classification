# Dog Breed Classification

This is the Capstone project done as part of Udacity's AWS Machine Learning Nanodegree program.

Project Overview:

The problem I have chosen to work on is to create a dog breed classifier. The aim is to detect a dog in an image and estimate the dog’s breed using a CNN. If an image of a human is given, the algorithm will estimate the resembling dog breed.

A machine learning approach to image classification involves identifying and extracting key features from images and using them as input to a machine learning model. With this method, the computers are taught to recognize the visual elements within an image.
CNNs are especially sophisticated in the domain of computer vision. They are a class of deep neural networks and are inspired by the human brain. They are composed of 3 - dimensional layers.

The reason I have chosen this project is because I am interested in learning about the methods and algorithms used to solve problems involving image data. Also, solving the dog breed classification problem is not easy even for a human. There are similar looking dogs belonging to different breeds and differently looking dogs from the same breed.

The pipeline built here can be used within a web or mobile app, which could potentially take a user-supplied image as input and output the dog breed. This approach to image classification has many potential uses and can be used to solve many real life problems.

![](flowchart.png)

Problem Statement:

Given an image of a dog, estimate and output the dog’s breed. If a human’s image is given, output the dog breed the human resembles. 

The problem can be broken down into the following steps:

1. Check whether the input image contains a dog. If it does, estimate the dog’s breed.
2. If no dog is detected, check whether the image contains a human face. If it does, estimate the dog breed the human face most closely resembles.
3. If neither a dog nor a human have been detected in the image, output an error message.
