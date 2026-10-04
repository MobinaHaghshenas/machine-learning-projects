# House Price Prediction

A regression project for predicting residential property prices using the Ames Housing dataset and comparing multiple machine learning regression algorithms.

## Overview

The objective is to predict house sale prices from a combination of numerical and categorical property features.

The dataset contains **1,460 observations and 80 features**, covering property characteristics such as:

- Living area
- Overall quality
- Year built
- Basement characteristics
- Neighborhood
- Number of bathrooms and bedrooms
- Garage and exterior characteristics
- Other structural and property attributes

## Data Preparation

The preprocessing pipeline includes:

- Exploratory data analysis
- Missing-value analysis
- Correlation analysis
- Feature selection based on correlation
- One-hot encoding of categorical variables
- Feature standardization
- Train-test splitting

## Models

Several regression approaches were implemented and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression
- XGBoost Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Decision Tree Regressor
- AdaBoost Regressor

Models were evaluated using:

- MAE
- MSE
- RMSE
- R²
- Cross-validation RMSE

## Results

The best recorded model was **Ridge Regression**.

| Metric | Result |
|---|---:|
| MAE | 15,736.32 |
| MSE | 476,888,545.82 |
| RMSE | 21,837.78 |
| R² | 0.8429 |
| Cross-Validation RMSE | 23,118.09 |

Ridge Regression achieved the lowest recorded cross-validation RMSE among the evaluated models.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Dataset

**Ames Housing Dataset**

File: `ames-housing-prices.csv`

## Project Files

- `house-price-prediction.ipynb` — complete preprocessing, modeling, evaluation and comparison workflow
- `ames-housing-prices.csv` — dataset
- `results/` — generated model evaluation results and visualizations
- `readme.md` — project documentation
