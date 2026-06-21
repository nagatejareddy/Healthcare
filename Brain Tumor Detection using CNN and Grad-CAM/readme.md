
# 🧠 Explainable Brain Tumor Detection using CNN and Grad-CAM

## Overview

This project presents an Explainable Artificial Intelligence (XAI) framework for Brain Tumor Detection from MRI scans using Convolutional Neural Networks (CNNs) and Grad-CAM visualization.

Unlike traditional classification models that only provide predictions, this system highlights the MRI regions responsible for the model's decision through heatmap-based localization.

---

## Features

* MRI Image Preprocessing
* CNN-based Brain Tumor Classification
* Tumor / No Tumor Detection
* Confidence Score Prediction
* Grad-CAM Explainability
* Heatmap Generation
* Tumor Localization Visualization
* Automated Diagnostic Analysis

---

## Workflow

MRI Scan → Preprocessing → CNN Feature Extraction → Classification → Grad-CAM Analysis → Heatmap Generation → Tumor Localization

---

## Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Matplotlib

---

## Model Architecture

Input Image (224×224×3)

Conv2D(32) → MaxPooling

Conv2D(64) → MaxPooling

Conv2D(128) → MaxPooling

Flatten

Dense(128)

Dropout(0.5)

Dense(1, Sigmoid)

---

## Explainable AI

Grad-CAM is used to visualize the regions that contributed most to the CNN prediction.

Red/Yellow Regions:
High influence on prediction

Blue Regions:
Low influence on prediction

---

## Results

Prediction: Tumor Detected

Confidence: 82.74%

Grad-CAM successfully highlighted tumor-related regions in MRI scans.

---

## Future Enhancements

* Tumor Boundary Detection
* Tumor Size Estimation
* Multi-Class Tumor Classification
* Streamlit Deployment
* Clinical Report Generation

---

## Author

Naga Teja Reddy Yerram Reddy

AI/ML | Computer Vision | Robotics | Autonomous Systems
