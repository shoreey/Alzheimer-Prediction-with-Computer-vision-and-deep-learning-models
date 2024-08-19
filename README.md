# Alzheimer's Disease Stage Prediction from MRI Images

## Project Overview
This project aims to build an end-to-end model to predict the stage of Alzheimer's disease from MRI (Magnetic Resonance Imaging) images. We use deep learning techniques to classify MRI scans into four different stages of Alzheimer's.

## Dataset
The dataset consists of MRI images divided into training and test sets. Images are classified into four categories:

0. Mild Demented
1. Moderate Demented
2. Non Demented
3. Very Mild Demented

Dataset statistics:
- Total images: 6,400
- Training set: 5,121 images
- Test set: 1,279 images

## Methodology

### Data Preparation
- Used PyTorch's ImageFolder to load images into datasets
- Applied random transformations to training images for data augmentation
- Split training data to create a validation set

### Model Architecture
We experimented with three different deep learning architectures:

1. ResNet50
2. VGG
3. EfficientNet

### Training
- Implemented supervised learning using PyTorch
- Used DataLoaders for efficient batch processing
- Applied various data augmentation techniques during training

## Results
please refere to the pdf and the code


## Future Work
- Experiment with ensemble methods
- Implement cross-validation for more robust evaluation
- Explore other state-of-the-art architectures


This project demonstrates the application of deep learning in medical image analysis, specifically for Alzheimer's disease prediction. It showcases the use of transfer learning and various CNN architectures for tackling a multi-class classification problem in healthcare.
