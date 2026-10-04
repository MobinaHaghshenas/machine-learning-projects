# Credit Card Customer Segmentation

An unsupervised machine learning project for segmenting credit card customers based on their behavioral and financial characteristics.

## Overview

The goal of this project is to identify meaningful customer groups without predefined labels.

The analysis explores customer behavior, detects potential outliers, and compares clustering approaches to determine suitable customer segments.

## Approach

The workflow includes:

- Data loading and quality inspection
- Missing-value analysis
- Outlier analysis
- Exploratory data analysis
- Feature analysis and visualization
- K-Means clustering
- Elbow method analysis
- Silhouette-based cluster selection
- DBSCAN clustering
- Comparison of clustering structures and detected outliers

## Clustering Results

### K-Means

The Elbow Method did not provide a clear single optimal point, so silhouette analysis was used to compare possible cluster configurations.

The selected configuration was:

**K = 4**

### DBSCAN

The selected configuration was:

- `eps = 4000`
- `min_samples = 6`

The resulting clustering structure identified customer groups together with potential outliers.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- K-Means
- DBSCAN

## Dataset

**Credit Card Customer Data**

File: `Credit Card Customer Data.csv`

The dataset contains customer-level behavioral and financial attributes suitable for unsupervised customer segmentation.

## Project Files

- `credit-card-customer-segmentation.ipynb` — complete clustering workflow
- `Credit Card Customer Data.csv` — dataset
- `readme.md` — project documentation
