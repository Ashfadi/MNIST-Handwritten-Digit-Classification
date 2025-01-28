# 🧠 MNIST Handwritten Digit Classification

This repository contains a **Convolutional Neural Network (CNN) model** implemented **from scratch** to classify **handwritten digits** from the MNIST dataset. This project is part of **Computer Vision Assignment 2**.

---

## 📌 Features
- **CNN Model**: Built from scratch using PyTorch with **10 convolutional layers** and **3 fully connected layers**.
- **MNIST Classification**: Classifies handwritten digits (0-9).
- **Cross-Entropy Loss**: Used for training the model.
- **Confusion Matrix**: Generates a confusion matrix to evaluate performance.
- **Batch Normalization & Residual Connections** (*Bonus*) included for improved accuracy.

---

## 🛠 Methodology
### 1️⃣ Dataset: MNIST
- The **MNIST dataset** consists of **28x28 grayscale images** of digits (0-9).
- Downloaded using PyTorch’s `torchvision.datasets.MNIST()`.

### 2️⃣ CNN Architecture
- **10 Convolutional Layers** with ReLU activation.
- **Max Pooling** layers for feature down-sampling.
- **3 Fully Connected Layers (MLP)** for classification.
- **Batch Normalization & Residual Connections** for better learning (bonus).

### 3️⃣ Training & Evaluation
- **Cross-Entropy Loss** for classification.
- **Adam Optimizer** with **learning rate scheduling**.
- **Confusion Matrix** to analyze misclassifications.

### 📊 Results
#### Model Performance
- **Test Accuracy**: Achieved ~98% accuracy on MNIST.
- **Confusion Matrix**: Displays correct vs. misclassified digits.
#### - Observations:
- Common misclassifications occur between 4 and 9.
- Batch Normalization improves convergence speed.
