# Bank Marketing Anomaly Detection

An anomaly detection project on the Bank Marketing dataset, focusing on identifying rare positive cases using unsupervised outlier detection techniques.

## Overview

The dataset contains 41,188 customer records with demographic, campaign-related, and economic features. The target variable is highly imbalanced, with approximately 12% positive cases.

The project investigates whether statistical feature selection and anomaly detection methods can distinguish the rare cases from the majority of observations.

## Approach

The workflow includes:

- Data quality inspection and missing-value analysis
- Categorical feature encoding using `LabelEncoder`
- Exploratory data analysis
- Statistical feature selection using Z-tests
- Separation of normal observations and rare positive cases
- Anomaly detection using:
  - Isolation Forest
  - Local Outlier Factor (LOF)
- Evaluation of anomaly detection performance on normal and rare cases
- Comparison of models under different data sampling scenarios

## Results

Two anomaly detection approaches were evaluated.

### Initial Scenario

| Model | Normal Detection | Rare-Case Detection |
|---|---:|---:|
| Isolation Forest | 77.74% | 67.31% |
| Local Outlier Factor | 81.88% | 33.34% |

A second scenario introduced a balanced subsample containing inliers and selected outliers:

| Model | Normal Detection | Rare-Case Detection |
|---|---:|---:|
| Isolation Forest | 55.72% | 70.91% |
| Local Outlier Factor | 62.50% | 53.34% |

The experiments demonstrate how sampling strategy and the presence of outliers can significantly affect anomaly detection performance.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn
- Isolation Forest
- Local Outlier Factor

## Dataset

**Bank Marketing Dataset**

File: `bank-marketing.csv`

The dataset contains customer and marketing campaign information used to analyze rare positive cases.

## Project Files

- `bank-marketing-anomaly-detection.ipynb` — complete analysis and modeling workflow
- `bank-marketing.csv` — dataset
- `readme.md` — project documentation
