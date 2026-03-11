# CIFAR-10 Image Classification using Convolutional Neural Network (CNN)

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset using TensorFlow and Keras.

## Project Overview
The goal of this project is to build and train a deep learning model that can automatically classify images into 10 different categories such as airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Dataset
CIFAR-10 is a well-known benchmark dataset in computer vision consisting of:
- 60,000 color images
- Image size: 32×32 pixels
- 10 different classes

The dataset is divided into:
- 50,000 training images
- 10,000 test images

## Model Architecture
The CNN architecture used in this project includes:

- Convolutional Layers (Conv2D)
- Batch Normalization
- ReLU Activation
- MaxPooling Layers
- Dropout for regularization
- Fully Connected Dense Layers
- Softmax output layer for multi-class classification

## Workflow
1. Import required libraries
2. Load the CIFAR-10 dataset
3. Visualize sample images
4. Data preprocessing
5. One-hot encoding of labels
6. Build CNN model
7. Train the model
8. Evaluate model performance

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn

## Learning Outcome
Through this project, I practiced:
- Building CNN architectures
- Image preprocessing
- Deep learning model training
- Model evaluation for image classification

## Future Improvements
- Data augmentation
- Transfer learning (ResNet, VGG)
- Hyperparameter tuning
- Improving model accuracy
