# Cats vs Dogs Classification using CNN

A Convolutional Neural Network (CNN) based image classification project to distinguish between cats and dogs. This project is built using TensorFlow/Keras and demonstrates the use of deep learning for binary image classification tasks.

---

## Project Overview

This project trains a CNN to classify images of cats and dogs from a labeled dataset. It includes:

- Data preprocessing (resizing, normalization)
  
- Building and training a CNN model using Keras
  
- Evaluating the model using validation data

- Making predictions on test images

---

## Model Architecture

A typical architecture used:  
Input (256x256x3) → Conv2D (32, 3x3, L2) → ReLU → MaxPooling2D  
→ Conv2D (64, 3x3, L2) → ReLU → MaxPooling2D  
→ Conv2D (128, 3x3, L2) → ReLU → MaxPooling2D  
→ Flatten → Dense (128, L2) → ReLU → Dense (64, L2) → ReLU → Dense (1) → Sigmoid


---

## Dataset Download

Dataset used: [Dogs vs Cats by Salader on Kaggle](https://www.kaggle.com/datasets/salader/dogs-vs-cats)

---

