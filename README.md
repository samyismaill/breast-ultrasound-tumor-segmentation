 Breast Ultrasound Tumor Segmentation

 Deep Learning project using ResNet50 + U-Net to segment breast tumors from ultrasound images.

 Goal: Detect and segment tumor regions to assist early breast cancer diagnosis.

 Best Results:
- Training Accuracy: ~97%
- Validation Accuracy: ~75%
- Test Accuracy: ~69%# Breast Ultrasound Tumor Segmentation using ResNet & U-Net

## Overview
This project focuses on breast tumor segmentation and classification using deep learning techniques on ultrasound medical images.

A pre-trained ResNet backbone combined with a U-Net segmentation architecture was used to accurately detect and segment tumor regions from breast ultrasound scans.

The project aims to support early breast cancer diagnosis through AI-powered medical image analysis.

---

## Features
- Breast tumor segmentation using U-Net
- Transfer Learning with ResNet50
- Medical image preprocessing and augmentation
- Tumor localization from ultrasound images
- Performance evaluation using Dice Score and IoU
- Visualization of predicted segmentation masks

---

## Model Architecture
- ResNet50 (Pre-trained on ImageNet)
- U-Net Decoder for segmentation
- Transfer Learning & Fine-Tuning

---

## Dataset
Dataset used:
- Breast Ultrasound Images Dataset (BUSI)

Classes:
- Benign
- Malignant
- Normal

---

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## Results

### Classification Performance
- Training Accuracy: ~97%
- Validation Accuracy: ~75.6%
- Test Accuracy: ~69.2%

### Segmentation Performance
- Successful tumor boundary localization
- Strong predicted mask alignment with ground truth

---

## Evaluation Metrics
- Dice Score
- IoU (Intersection over Union)
- Accuracy
- Loss Curves

---

## Author
Samy Ismail
