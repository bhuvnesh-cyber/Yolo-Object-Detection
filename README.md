# Yolo-Object-Detection

## Introduction
Object Detection is a task in Artificial Intelligence that focuses on detecting objects in images. Yolo is one of the best available models for Object Detection at the moment. Here we use its capabilities to detect a tree in custom images and videos

## Goal 🎯

This project presents a novel methodology based on the latest YOLO object detector for detecting trees in a video and images captured in a area that includes trees of different sizes, resolution, ground spread, degree of overlap, etc.

## Apporach
* Fed some random images with tree to the model and these were the outputs:

![Capture1](https://user-images.githubusercontent.com/57914889/164889403-d9ca7e5f-b3e0-459e-804a-b9d719efe32e.PNG)

![Capture](https://user-images.githubusercontent.com/57914889/164889404-0959c1f5-0ec0-48f8-af3c-d474110a086c.PNG)

* Similarly Fed a random video with tree to the model and these were the outputs:

![Capture2](https://user-images.githubusercontent.com/57914889/164889398-584deb78-299a-440b-8fe5-cc8bc9b24a6f.PNG)

## YOLO
You Only Look Once is an object detection network. It localizes and classifies an object. It does both these tasks in a single step. The backbone of YOLO in the darknet-53 neural network, there are 53 convolutional layers in the network for feature extraction.

## Opinion
This project was challenging but quite interesting as well, the results were amazing the model could easily find a tree in the video and an image and create a bounding box around it.

## Working enviroment
Google Colab
  - Numpy
  - Glob
  - Opencv
