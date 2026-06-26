
#  CIFAR-10 Image Classification using ResNet50

## 📌 Overview

This project implements an image classification system using **Deep Learning** and **Transfer Learning** with the **ResNet50 architecture**.

The goal is to train a model capable of recognizing objects from images and predicting their class.

The project uses the **CIFAR-10 dataset**, which contains 10 different object categories.

---

## 🎯 Objective

Build an AI model that can:

- Load and preprocess images
- Train a ResNet50-based classifier
- Evaluate model performance
- Predict the class of a new uploaded image

---

## 🧠 Model Architecture

The model is based on **ResNet50 (Residual Network)**.

ResNet introduces **skip connections (residual blocks)** that allow deeper neural networks to learn efficiently and avoid the vanishing gradient problem.


---

## 📂 Dataset

Dataset used:

**CIFAR-10**

Classes:

- ✈️ Airplane
- 🚗 Automobile
- 🐦 Bird
- 🐱 Cat
- 🦌 Deer
- 🐶 Dog
- 🐸 Frog
- 🐴 Horse
- 🚢 Ship
- 🚚 Truck

Dataset size:

- Training images: 50,000
- Testing images: 10,000
- Image size: 32×32×3

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab

---

## 🔄 Workflow

1. Import and prepare the dataset

2. Normalize images

3. Build ResNet50 model

4. Train the model

5. Evaluate using:

- Accuracy
- Loss
- Validation metrics

6. Test prediction on new images

## 📈 Model Performance

After training:

- Training Accuracy: ~91%
- Validation Accuracy: ~93%

The validation accuracy is slightly higher than training accuracy, which indicates good generalization and no significant overfitting.

---

## 🔮 Prediction Example

The model can take a new image and predict its class



