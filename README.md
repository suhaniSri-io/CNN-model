# 🔢 MNIST Digit Classification using CNN

## Overview

A simple deep learning project that uses a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) from the MNIST dataset.

## Features

* Uses the MNIST dataset from TensorFlow
* Preprocesses and normalizes image data
* Builds and trains a CNN model
* Evaluates model accuracy on test data
* Predicts handwritten digits
* Saves the trained model

## Model Architecture

* Conv2D (32 filters) → MaxPooling
* Conv2D (64 filters) → MaxPooling
* Flatten
* Dense (128, ReLU)
* Dense (10, Softmax)

## Technologies Used

* Python
* TensorFlow/Keras
* NumPy
* Matplotlib
* Jupyter Notebook

## Workflow

1. Load and preprocess the MNIST dataset
2. Train the CNN model
3. Evaluate model performance
4. Predict digit classes
5. Save the trained model

## Files

├── cnn.ipynb

└── README.md

## Author

Suhani Srivastava

A beginner-friendly CNN project that classifies handwritten digits from the MNIST dataset using TensorFlow and Keras.
