
# Machine Learning Projects

A collection of practical machine learning projects covering supervised learning, unsupervised learning, anomaly detection, classification, regression, and customer segmentation.

The projects are implemented in Python using real-world tabular datasets, with an emphasis on data preprocessing, feature engineering, model selection, evaluation, and comparison.

## Projects

| Project | Type | Main Techniques |
|---|---|---|
| [Bank Marketing Anomaly Detection](./bank-marketing-anomaly-detection/) | Anomaly Detection | Isolation Forest, LOF, Statistical Feature Selection |
| [Breast Cancer Classification](./breast-cancer-classification/) | Classification | Perceptron, MLP, PyTorch Neural Networks |
| [Credit Card Customer Segmentation](./credit-card-customer-segmentation/) | Clustering | K-Means, DBSCAN |
| [House Price Prediction](./house-price-prediction/) | Regression | Ridge, Lasso, Linear Regression, Random Forest, XGBoost, Gradient Boosting |
| [Pumpkin Seed Classification](./pumpkin-seed-classification/) | Classification | Random Forest, Hyperparameter Tuning, Feature Importance |

---

## 1. Bank Marketing Anomaly Detection

An anomaly detection project using customer and marketing campaign data.

The workflow includes categorical encoding, exploratory data analysis, statistical feature selection using Z-tests, and comparison of Isolation Forest and Local Outlier Factor under different sampling scenarios.

**Key techniques:**

- Statistical feature selection
- Isolation Forest
- Local Outlier Factor
- Outlier detection
- Imbalanced data analysis

[View Project →](./bank-marketing-anomaly-detection/)

---

## 2. Breast Cancer Classification

A binary classification project using the Breast Cancer Wisconsin dataset.

The project contains both classical machine learning and neural network approaches, including preprocessing, missing-value treatment, duplicate removal, outlier handling, feature scaling, class balancing, cross-validation, and MLP experiments.

The best recorded neural-network experiment achieved:

- **97.44% test accuracy**
- **0.974 AUC**
- **96.88% recall**

**Key techniques:**

- Data preprocessing
- Min-Max scaling
- NearMiss undersampling
- Perceptron
- Multi-Layer Perceptron
- PyTorch
- Model evaluation

[View Project →](./breast-cancer-classification/)

---

## 3. Credit Card Customer Segmentation

An unsupervised learning project focused on discovering customer segments from credit card behavioral and financial data.

Multiple clustering approaches were investigated rather than relying on a single algorithm.

**Key techniques:**

- Exploratory data analysis
- K-Means clustering
- Elbow method
- Silhouette analysis
- DBSCAN
- Outlier detection

The selected K-Means configuration used **4 clusters**, while DBSCAN was evaluated with `eps=4000` and `min_samples=6`.

[View Project →](./credit-card-customer-segmentation/)

---

## 4. House Price Prediction

A regression project for predicting residential property prices using the Ames Housing dataset.

The project compares multiple regression algorithms and evaluates them using several complementary metrics.

**Models evaluated:**

- Linear Regression
- Ridge Regression
- Lasso Regression
- XGBoost
- Random Forest
- Gradient Boosting
- Decision Tree
- AdaBoost

The best recorded model was **Ridge Regression**, achieving:

- **R²: 0.8429**
- **RMSE: 21,837.78**
- **MAE: 15,736.32**
- **Cross-validation RMSE: 23,118.09**

[View Project →](./house-price-prediction/)

---

## 5. Pumpkin Seed Classification

A supervised classification project using morphological characteristics of pumpkin seeds.

The project covers preprocessing, exploratory analysis, outlier handling, Random Forest classification, hyperparameter tuning, and feature importance analysis.

The tuned Random Forest model achieved:

- **88.86% accuracy**

The most important features included:

- Eccentricity
- Aspect Ratio
- Compactness
- Roundness
- Major Axis Length

[View Project →](./pumpkin-seed-classification/)

---

## Skills Demonstrated

Across these projects, the repository demonstrates practical experience with:

### Data Preparation

- Missing-value analysis
- Duplicate detection
- Outlier detection and removal
- Categorical encoding
- Feature scaling
- One-hot encoding
- Feature selection
- Class imbalance handling

### Supervised Learning

- Classification
- Regression
- Perceptron
- Multi-Layer Perceptron
- Random Forest
- Ridge and Lasso Regression
- Gradient Boosting
- XGBoost
- AdaBoost

### Unsupervised Learning

- K-Means
- DBSCAN
- Silhouette analysis
- Elbow method
- Anomaly detection

### Model Evaluation

- Accuracy
- Precision
- Recall
- F1 Score
- AUC
- Confusion Matrix
- MAE
- MSE
- RMSE
- R²
- Cross-validation

### Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- XGBoost
- SciPy
- Matplotlib
- Seaborn
- Imbalanced-learn
- Jupyter Notebook

---

