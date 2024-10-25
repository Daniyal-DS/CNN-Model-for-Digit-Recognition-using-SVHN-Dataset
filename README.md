# CNN Model for Digit Recognition Using SVHN Dataset
This repository contains a Convolutional Neural Network (CNN) model developed to recognize digits (0-9) from images in the Street View House Numbers (SVHN) dataset. The SVHN dataset provides real-world digit images, often used to benchmark machine learning models for image classification.

# Project Overview
The objective of this project is to accurately classify digit images from the SVHN dataset using a CNN model built with TensorFlow and Keras. CNNs are particularly effective for this purpose due to their ability to learn spatial hierarchies in images, which helps them excel in image recognition tasks.

# Features
 Dataset: 
  The SVHN dataset includes over 600,000 digit images taken from real-world scenes, such as house numbers, with varying lighting, angles, and resolutions.
 Data Preprocessing:
Resizing and normalizing images for consistency.
Converting labels to categorical format.
Augmenting data to enhance model generalization.

 Model Architecture:
Multiple convolutional layers with ReLU activations and max pooling layers to capture and reduce image features.
Fully connected layers for transforming features into class scores.
Dropout layers to prevent overfitting and improve generalization.

 Evaluation Metrics:
Accuracy and loss are monitored, with validation checks to ensure performance consistency.
