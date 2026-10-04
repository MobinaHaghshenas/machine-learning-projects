# Pumpkin Seed Classification

A supervised machine learning project for classifying pumpkin seed varieties using morphological characteristics extracted from seed images.

## Overview

The project uses numerical morphological features to distinguish between pumpkin seed classes.

The analysis focuses on preprocessing, feature relationships, class distribution, outlier handling, Random Forest classification, hyperparameter tuning, and feature importance.

## Data Preparation

The workflow includes:

- Missing-value analysis
- Categorical feature encoding
- Feature scaling
- Exploratory data analysis
- Class distribution analysis
- Outlier detection and removal
- Train-test splitting

## Model

A Random Forest classifier was trained and then tuned using different hyperparameter configurations.

The main hyperparameters investigated include:

- Number of estimators
- Minimum samples required for splitting

The selected configuration was:

- `n_estimators = 350`
- `min_samples_split = 2`

## Results

The final tuned model achieved:

- **Accuracy: 88.86%**

Confusion matrix:

```text
[[331, 29],
 [ 50, 299]]
 ```
The classification results show relatively balanced performance across the two classes.

## Feature Importance
The five most important features identified by the Random Forest model were:
1. Eccentricity
2. Aspect Ratio
3. Compactness
4. Roundness
5. Major Axis Length

These features provide useful information for distinguishing pumpkin seed varieties based on their morphology.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Random Forest

## Dataset
**Pumpkin Seeds Dataset**

File: `Pumpkin_Seeds_Datase.csv`

## Project Files
- `pumpkin-seed-classification.ipynb` — complete classification and model tuning workflow
- `Pumpkin_Seeds_Datase.csv` — dataset
- `readme.md` — project documentation
