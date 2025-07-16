# Skin Cancer Detection and Classification Using CNN

This project implements deep learning techniques to detect and classify skin cancer using Convolutional Neural Networks (CNNs). Skin cancer is a critical health issue worldwide, and early, accurate diagnosis can significantly improve patient outcomes. This work focuses on binary classification of skin lesions and uses a binary cascading model approach for enhanced performance.

## Project Overview

- **Objective:** Build and evaluate CNN models for **binary classification** of skin lesions (e.g., benign vs malignant).
- **Datasets Used:**  
  - **ISIC Dataset:** Two CNN models trained on the ISIC dataset.  
  - **HAM10000 Dataset:** Two CNN models trained on the HAM10000 dataset.
- **Model Types:**  
  - **Binary Classification Models:** CNNs trained to distinguish between two classes — typically benign vs malignant lesions.  
  - **Binary Cascading Models:** A two-stage binary classification approach where the first model detects whether the lesion is suspicious or not, and the second model further classifies suspicious lesions into specific cancerous types.

## Features

- Binary classification for clear differentiation between benign and malignant skin lesions.
- Binary cascading model improves classification accuracy by breaking down the decision process into sequential binary steps.
- Extensive data preprocessing and augmentation to enhance model generalization.
- Evaluation metrics include accuracy, precision, recall, F1-score, and ROC-AUC.
- Models trained separately on ISIC and HAM10000 datasets to validate across diverse image sources.

## Usage

1. Prepare and preprocess ISIC and HAM10000 datasets.
2. Train or load pretrained CNN models for binary classification and binary cascading.
3. Evaluate model performance using provided test sets.
4. Use trained models to predict skin lesion class from new images.

