# Handwritten Character Recognition

## Project Description

This project implements a **Handwritten Character Recognition System** using a pre-trained Convolutional Neural Network (CNN). The system recognizes handwritten digits from the **MNIST dataset** and can also predict digits from a user-uploaded handwritten image.

The project does not train a new model. Instead, it uses an already trained CNN model and focuses on data preprocessing, prediction, evaluation, and handwritten image recognition.

A preprocessing pipeline is included for custom images so that a handwritten digit can be detected even when it is not centered in the uploaded image. The system automatically detects the digit, removes unnecessary background, crops it, resizes it while maintaining its shape, centers it in a 28×28 image, and sends it to the pre-trained CNN model.

## Features

- Uses the MNIST handwritten digit dataset
- Uses a pre-trained CNN model
- No model training required
- Automatically downloads the dataset and model
- Predicts MNIST test images
- Calculates test accuracy
- Generates a classification report
- Generates a confusion matrix
- Allows users to upload their own handwritten digit
- Detects the digit automatically from anywhere in the uploaded image
- Crops and preprocesses the detected digit
- Converts the image to MNIST-style 28×28 format
- Automatically centers the digit
- Displays prediction confidence
- Saves prediction results to a CSV file

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Hugging Face Hub
- Google Colab

## Dataset

The project uses the MNIST dataset, which contains grayscale images of handwritten digits from 0 to 9.

Each image has a resolution of:

28 × 28 pixels
