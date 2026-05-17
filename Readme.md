Computer Vision Problem Formulation and CNN Prototype
Project Overview

This project focuses on solving a Computer Vision problem using a Convolutional Neural Network (CNN). The dataset contains images categorized into different defect classes such as Normal, Scratch, Dent, and Stain.

The objective of this project is to preprocess image data, analyze the dataset, and build a CNN model capable of classifying images into their respective categories.

Problem Type
Selected Problem:

Image Classification

Reason:

The dataset contains labeled images divided into different classes. Each image belongs to only one category, and the CNN model predicts the correct class label for the input image.

Dataset Information
Classes in Dataset
Normal
Scratch
Dent
Stain
Dataset Features
RGB Images
Fixed image size after preprocessing: 96×96
Balanced dataset
Tasks Performed
Task 1: Problem Identification
Identified the dataset as an Image Classification problem.
Explained why classification is appropriate.
Task 2: Dataset Exploration

Performed:

Class analysis
Image count analysis
Image dimension analysis
Dataset balance analysis
Visualization of sample images
Task 3: Image Preprocessing

Applied preprocessing techniques such as:

Image resizing
Pixel normalization
Train-test splitting
Data augmentation
Augmentation Techniques
Rotation
Horizontal flipping
Zooming
Task 4: CNN Model Creation
CNN Layers Used
Convolution Layer
ReLU Activation Function
Max Pooling Layer
Flatten Layer
Dense Layer
Output Layer
Framework Used
TensorFlow
Keras
Technologies Used
Python
TensorFlow
Keras
NumPy
Matplotlib
Model Workflow
Load Dataset
Preprocess Images
Apply Augmentation
Build CNN Architecture
Train CNN Model
Evaluate Accuracy
Predict Image Classes
Expected Output

The CNN model learns visual features from images and classifies them into:

Normal
Scratch
Dent
Stain
Conclusion

This project demonstrates how Convolutional Neural Networks (CNNs) can be used for image classification tasks in computer vision. The model learns patterns from images using convolution, pooling, activation functions, and dense layers to accurately classify defects