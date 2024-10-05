# Breast_Cancer_Classification
# Breast Tumor Detection Using Deep Learning

## Overview

This repository contains code and resources for detecting breast tumors in mammogram images using deep learning techniques. The project leverages several pre-trained models, including Inception V3, VGG16, and ResNet50, to classify mammogram images. The dataset consists of 3,383 annotated mammogram images, exported from Roboflow, organized in a folder structure.

## Dataset

- **Name**: Breast Tumor Mammography Dataset
- **Size**: 3,383 images
- **Annotations**: Images are focused on breast tumors, organized in directories for binary classification.
- **Source**: The dataset is obtained from [Roboflow](https://roboflow.com).

## Models

1. **Inception V3**
   - A deep convolutional neural network architecture that uses various kernel sizes to capture features at different scales.
   - The model was fine-tuned for better performance on the mammogram dataset.

2. **VGG16**
   - A well-known architecture characterized by its simplicity and depth, using 3x3 convolutional layers and max-pooling layers.

3. **ResNet50**
   - A deep residual network that includes skip connections to improve gradient flow during training, allowing for training of deeper networks without degradation.

## Requirements

Make sure you have the following libraries installed:

```bash
pip install tensorflow keras matplotlib seaborn scikit-learn
