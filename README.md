# Deep Face Recognition using Keras and TensorFlow

This repository demonstrates the process of building a face recognition system using Keras and TensorFlow. The process can be divided into four major steps:

### Steps:
a. **Face Detection/Identification:** Utilize Dlib and OpenCV to detect and identify faces in an image.

b. **Preprocessing:** Convert images to grayscale and crop them to 200x200 pixels for consistency.

c. **Convolutional Neural Network (CNN) Design:** Design a CNN architecture using Keras for feature extraction.

d. **Model Training:** Train the CNN model on the training dataset and evaluate its performance on testing data.

### Understanding Convolutional Neural Networks (CNNs):
CNNs are highly effective in image recognition and classification tasks. They operate through four main operations:
- **Convolution**
- **Non-Linearity (ReLU)**
- **Pooling or Subsampling**
- **Classification (Fully Connected Layer)**

These operations are fundamental in CNNs and form the building blocks for feature extraction and classification.

### Image Representation:
An image is represented as a matrix of pixel values, where each pixel corresponds to a specific value. Grayscale images have a single channel, while color images typically have three channels (red, green, blue).

### VGG-Face Model:
This repository utilizes the VGG-Face model, derived from the VGG16 architecture originally used for object recognition in the ImageNet competition. The VGG-Face model is adapted for face recognition tasks and consists of convolutional layers, ReLU activations, max-pooling, and softmax layers.

### Technical Specifications:
- **Python Version:** 3.5
- **Dependencies:** numpy, scipy, dlib, OpenCV, Keras, TensorFlow
- **Backend:** TensorFlow (configured in Keras JSON file)
- **Dataset:** Create your own dataset for training and testing purposes.

### About Keras:
Keras is a high-level neural network library written in Python. It offers a simple and modular interface, making it easy to build complex neural network models. Keras abstracts low-level libraries like TensorFlow and Theano, simplifying the implementation process.
