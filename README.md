# Task 3: Dataset Preparation and Preprocessing for Deep Learning

## Overview

This project implements dataset preparation and preprocessing techniques for
deep learning using the CIFAR-10 image dataset.

The objective is to perform exploratory data analysis, data quality checking,
image preprocessing, augmentation, feature transformation, and
train-validation-test splitting.

## Dataset

The CIFAR-10 dataset contains 60,000 color images of size 32 × 32 pixels
belonging to 10 classes.

### Classes

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow / Keras
- Scikit-learn

## Tasks Performed

- Dataset loading
- Exploratory Data Analysis (EDA)
- Class distribution analysis
- Image visualization
- Missing-value checking
- Infinite-value checking
- Duplicate image checking
- Image dimension checking
- Pixel value analysis
- RGB channel analysis
- Train-validation-test splitting
- Pixel normalization
- Label encoding
- Image augmentation
- Visualization of augmented images
- Final data-quality analysis

## Dataset Split

The original CIFAR-10 training dataset was divided into:

| Dataset | Images |
|---|---:|
| Training | 45,000 |
| Validation | 5,000 |
| Testing | 10,000 |

The test dataset was kept separate from the training and validation data.

## Preprocessing

The following preprocessing techniques were applied:

1. Converted image arrays to `float32`
2. Normalized pixel values from `0–255` to `0–1`
3. Applied one-hot encoding to class labels
4. Performed stratified train-validation splitting
5. Applied image augmentation

## Image Augmentation

The following augmentation techniques were used:

- Rotation: 15 degrees
- Width shift: 10%
- Height shift: 10%
- Horizontal flip
- Zoom: 10%

## Data Quality Results

- Missing values: 0
- Infinite values: 0
- Image dimensions: 32 × 32 × 3
- Number of classes: 10
- Pixel range after normalization: 0–1
- Exact duplicates in the checked sample: 0

## Results

The dataset was successfully prepared for subsequent deep learning
applications. EDA visualizations, class distributions, pixel analysis,
normalization results, and augmented images are included in the notebook.
