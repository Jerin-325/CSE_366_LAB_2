# CSE_366_LAB_2 Brain Tumor MRI Images 44 Classes Classification Using CNNs (PyTorch)

This project demonstrates how to classify brain tumor using Convolutional Neural Networks (CNNs). It includes a **pre-trained CNN** implementation using PyTorch.

> ⚠️ **Note**: This project is intended as a **showcase of my code** for educational and reference purposes. It is designed to help others understand and learn from the implementation rather than to achieve high-end or state-of-the-art performance. Extensive hyperparameter tuning or advanced data augmentation is **not** performed.

## 📂 Dataset

The dataset used in this project is publicly available on Kaggle:

- **Dataset**: Brain Tumor MRI Images 44 Classes
- **Local Path Used**: `https://www.kaggle.com/datasets/fernando2rad/brain-tumor-mri-images-44c`
- **Classes**: 44
- **Split Ratio**:
  - Train: 70%
  - Validation: 15%
  - Test: 15%

## 🧠 Model Architectures

### 1. Pre-trained CNN
A transfer learning approach using a pre-trained model `ResNet50`.
