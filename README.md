# Pothole-Image-Classification-with-CNNs
#  Pothole Image Classification with CNNs

This project focuses on developing a robust image classification system to detect road surface conditions using deep learning techniques. The goal is to classify road images into three categories: **Normal**, **Potholes**, and **Bumps**.

##  Project Highlights

- Convolutional Neural Networks (CNNs)
- VGG16 Backbone + Transformer Fusion
-  Multiscale Image Processing
-  Data Augmentation Techniques
-  GUI using Gradio for real-time prediction

---

## Dataset

The dataset includes images captured under various conditions with labels:
- `Normal`: Smooth roads
- `Potholes`: Damaged road surfaces
- `Bumps`: Raised surfaces or speed bumps

---

## Model Architecture

- **CNN Backbone**: VGG16
- **Transformer Layer**: Captures long-range dependencies
- **Fusion**: Combines CNN and Transformer outputs
- **Multiscale Input**: Enhances feature extraction across resolutions

---

##  Techniques Used

- **Data Augmentation**: Rotation, flipping, brightness adjustments
- **Normalization**
- **Transfer Learning** with VGG16, VGG19, 
DenseNet169, 
DenseNet201, Xception, InceptionV3, 
ResNet50V2, InceptionResNetV2
- **Fine-tuning** Transformer layers
- **Multiscale Fusion** for feature enhancement

---

##  GUI

A user-friendly interface built using **Gradio** allows:
- Uploading images
- Real-time prediction display
- Visual explanation of model confidence

---

##  Evaluation Metrics

- **Accuracy**
- **Precision, Recall, F1-score**
- **Confusion Matrix**
- **Loss and Accuracy Curves**

