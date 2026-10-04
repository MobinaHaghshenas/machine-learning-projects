# Breast Cancer Classification

A binary classification project using the Breast Cancer Wisconsin dataset, combining classical machine learning models with neural network approaches.

## Overview

The project focuses on classifying breast cancer cases into two classes using numerical diagnostic features.

Two complementary approaches are included:

1. Classical machine learning classification
2. Neural network classification using PyTorch

## Machine Learning Pipeline

The classical machine learning workflow includes:

- Missing-value analysis
- Median imputation
- Duplicate detection and removal
- Outlier detection and removal using the IQR method
- Min-Max feature scaling
- Stratified train-test splitting
- Class imbalance handling using NearMiss undersampling
- Model training and evaluation
- Cross-validation
- MLP hyperparameter tuning

The classical models include:

- Perceptron
- Multi-Layer Perceptron (MLP)

The best recorded classical result achieved:

- Test Accuracy: **92.31%**
- AUC: **0.920**
- F1 Score: **0.912**

## Neural Network Experiments

A separate PyTorch implementation evaluates multiple MLP architectures with different:

- Hidden-layer configurations
- Number of neurons
- Activation functions
- Learning rates
- Network depths

The best recorded neural-network configuration achieved:

- Test Accuracy: **97.44%**
- AUC: **0.974**
- Recall: **96.88%**
- Confusion Matrix: `[[45, 1], [1, 31]]`

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- PyTorch
- Matplotlib

## Dataset

**Breast Cancer Wisconsin (Original) Dataset**

The project includes the preprocessed dataset:

`breast-cancer-wisconsin-preprocessed.csv`

## Project Files

- `breast-cancer-classification.ipynb` — classical machine learning classification pipeline
- `breast-cancer-neural-network.ipynb` — PyTorch MLP experiments
- `breast-cancer-wisconsin-preprocessed.csv` — preprocessed dataset
- `readme.md` — project documentation
