# Diabetes Prediction Using Machine Learning

## Description

This project focuses on diabetes classification using machine learning techniques applied to the Pima Indians Diabetes Database.

The notebook covers data exploration, correlation analysis, class balancing, data preprocessing, dimensionality reduction, model training, cross-validation, and model evaluation.

## Dataset

The project uses the Pima Indians Diabetes Database.

The target variable is `Outcome`:

- `0` — No Diabetes
- `1` — Diabetes

## Exploratory Data Analysis

The notebook includes:

- Dataset loading
- Dataset structure and information
- Descriptive statistics
- Missing-value checking
- Analysis of the target variable distribution
- Correlation matrix visualization

## Data Preprocessing

The following preprocessing techniques are used:

- Random OverSampling to address class imbalance
- StandardScaler for feature standardization
- Principal Component Analysis (PCA) for dimensionality reduction

## Machine Learning Models

The following classification models are evaluated:

- Logistic Regression
- Random Forest
- Decision Tree
- Gradient Boosting
- XGBoost

## Model Evaluation

The models are evaluated using Stratified 5-Fold Cross-Validation.

The notebook calculates:

- Accuracy
- Precision
- Recall
- F1 Score
- Confidence intervals for accuracy

Confusion matrices are also generated for the best-performing fold of each model.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Imbalanced-learn
- XGBoost
- Jupyter Notebook

## Project Structure

```text
Machine-learning-project-for-diabetes-prediction/
│
├── data/
│   └── diabetes.csv
│
├── Diabetes_Prediction_Machine_Learning.ipynb
└── README.md
