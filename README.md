# dog_breed_project

This is repository contains my capstone project Dog Breed Classification for the machine learing engineer nano degree Udacity

## Project OverView

In this project we will build a machine learning model capable of processing real-world images provided by a user and classifying it. These images may be of dogs or humans, if the image is of a dog, the model will identify an estimate of the dog's breed. If an image of a human is provided, the model will identify the similar breed of dog. We will explore some types of Convolutional Neural Network (CNN) and architecture for classifying humans, dogs and breeds.

The main objective in this project is to create a CNN based model to classify the images. The main steps to be followed to achieve the goal are:

	- Import libraries and image datasets, make pre-processing steps on the data. Create training, validation and test datasets.
	- Create a human face detection classifier using OpenCV’s implementation of Haar feature-based cascade classifiers.
	- Create a pre-trained dog face classifier with model VGG16.
	- Create a CNN classifier to classify dog breeds from scratch, train, validate and test the model.
	- Create a classifier of dog breeds with CNN using knowledge transfer with resnet architecture. Train and test the model.
	- Combine the dog detector and the human detector and create an algorithm.
  
Make sure to download all datasets needed to train the model.

Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in this project's home directory, at the location /dogImages.

Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the home diretcory, at location /lfw.

## Original Repository

The original  Udacity project instructions (notebook...) can be found [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification).

## Dependencies

All necessary dependencies can be found at this [link](https://github.com/udacity/deep-learning-v2-pytorch).
## Acknowledgment

I would like to thank everyone who helped me carry out this project, the references used and udacity for all the knowledge transmitted throughout this nanodegree
