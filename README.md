# Deep_Fake_Image_Classification
## Introduction
Deep fake images have become a growing concern in today's digital age. This project aims to develop a machine learning model to accurately classify real and fake images using convolutional neural networks (CNNs). The goal is to detect manipulations in images and distinguish between authentic and altered content.

## Features
- Binary Classification: Classifies images as either real or fake.
- Pre-trained Model: Utilizes the VGG16 model to improve performance.
- Transfer Learning: Adds custom layers to fine-tune the pre-trained model for the dataset.

## Dataset
The dataset consists of images stored in two categories:

**Real**: Images that are authentic.
**Fake**: Images that are generated/manipulated to create deep fakes.
The dataset is split into training, validation, and testing sets for model evaluation.

## Model Architecture
The model uses the VGG16 architecture with added layers for classification:

**Input Layer**: Pre-trained VGG16 layers.
**Custom Layers**: Additional Dense, Dropout, and Activation layers for fine-tuning.
**Output Layer**: Sigmoid activation function for binary classification.
