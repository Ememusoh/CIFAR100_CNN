# CIFAR-100 Image Classification Using Convolutional Neural Networks (CNN)

This repository contains a Convolutional Neural Network (CNN) model designed to classify images from the CIFAR-100 dataset into 100 distinct categories. The project encompasses data preprocessing, model training, evaluation, and testing.

## Overview

The CIFAR-100 dataset presents a challenging image classification task with 100 classes, each containing 600 images. This project implements a CNN to effectively classify these images, achieving competitive performance metrics.

## Model Architecture

The CNN model comprises the following layers:

- **Input Layer**: Accepts 32x32 pixel RGB images.
- **Convolutional Layers**: Multiple layers with ReLU activation and max-pooling.
- **Fully Connected Layers**: Dense layers leading to the output.
- **Output Layer**: Softmax activation for multi-class classification.

## Training Configuration

- **Batch Size**: 64
- **Epochs**: 200 (ran severl times)
- **Optimizer**: Adam
- **Learning Rate**: 0.001
- **Loss Function**: Categorical Cross-Entropy

## Performance Metrics

The model's performance was evaluated on training, validation, and test datasets using the following metrics:

- **Accuracy**: Proportion of correctly classified images.
- **Precision**: Accuracy of positive predictions.
- **Recall**: Ability to identify positive cases.
- **Confusion Matrix**: Breakdown of true positives, true negatives, false positives, and false negatives.
- **Classification Report**: Includes precision, recall, and F1-score for each class.



### Training Metrics

- **Training Accuracy**: 85%
- **Training Precision**: 84%
- **Training Recall**: 83%

### Validation Metrics

- **Validation Accuracy**: 80%
- **Validation Precision**: 79%
- **Validation Recall**: 78%

### Test Metrics

- **Test Accuracy**: 78%
- **Test Precision**: 77%
- **Test Recall**: 76%

