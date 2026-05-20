# Hybrid Breast Cancer Detection

This repository contains the implementation of deep learning and hybrid CNN models for breast cancer classification using breast ultrasound (BUS) images.

## Models Included
- Custom CNN
- VGG16
- VGG19
- DenseNet121
- ResNet50
- ResNet50V2
- InceptionV3
- Xception
- Hybrid VGG16-DenseNet121

## Dataset
The BUSI breast ultrasound dataset used in this study is publicly available at:
https://scholar.cu.edu.eg/?q=afahmy/pages/dataset

## Proposed Framework
The proposed hybrid framework combines VGG16 and DenseNet121 using transfer learning and feature fusion for BUS image classification.

## Environment
The experiments were implemented using Python, TensorFlow, and Keras in Google Colab.
## Data Augmentation
A seven-stage augmentation strategy was implemented in this study to improve dataset diversity and reduce overfitting during training. The augmentation pipeline includes image transformation and preprocessing techniques integrated within the provided implementation code.
