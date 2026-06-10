# Brain Tumor Classification using Deep Learning

## Overview

This project implements a Convolutional Neural Network (CNN) to classify brain MRI images into four categories:

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

The model is trained using MRI scan images and can automatically predict the type of brain tumor present in the image.

---

## Problem Statement

Brain tumor diagnosis from MRI scans is a critical and time-sensitive task. Manual interpretation requires significant expertise and can be time-consuming.

This project aims to develop a Deep Learning-based solution that assists in automated brain tumor classification using MRI images.

---

## Dataset

The dataset contains MRI images categorized into:

1. Glioma
2. Meningioma
3. Pituitary
4. No Tumor

Images are divided into:

- Training Set
- Testing Set

---

## Project Workflow

1. Data Collection
2. Image Preprocessing
3. Image Resizing
4. Dataset Preparation
5. CNN Model Development
6. Model Training
7. Model Evaluation
8. Prediction and Classification

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Image

---

## Model Architecture

The CNN model consists of:

- Convolution Layer
- Max Pooling Layer
- Flatten Layer
- Fully Connected Dense Layers
- Softmax Output Layer

Output Classes:
- Glioma
- Meningioma
- Pituitary
- No Tumor

---

## Features

- MRI Image Classification
- Deep Learning-Based Prediction
- Automated Tumor Detection Support
- Multi-Class Classification
- Medical Image Analysis

---

## Future Improvements

- Transfer Learning using EfficientNet or ResNet
- Model Explainability using Grad-CAM
- Streamlit Web Application Deployment
- Improved Accuracy with Data Augmentation
- Real-Time MRI Classification System
