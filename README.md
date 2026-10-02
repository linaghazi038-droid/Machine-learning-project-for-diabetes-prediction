# Diabetes Prediction Using Machine Learning

## Description

This project focuses on predicting diabetes using machine learning techniques applied to the Pima Indians Diabetes Database.

The notebook includes data exploration, correlation analysis, class balancing using Random OverSampling, model training, and Stratified K-Fold Cross-Validation.

## Dataset

The project uses the Pima Indians Diabetes Database.

The target variable is `Outcome`:

- `1` — Diabetes
- `0` — No Diabetes

## Data Analysis

The notebook includes:

- Data loading
- Exploratory data analysis
- Dataset information and descriptive statistics
- Missing-value checking
- Distribution analysis of the target variable
- Correlation matrix visualization

## Data Preprocessing

Random OverSampling is applied to address the imbalance between the two classes.

## Machine Learning Models

The following classification models are evaluated:

- Logistic Regression
- Random Forest
- Gradient Boosting
- Decision Tree
- XGBoost

## Model Evaluation

The models are evaluated using Stratified 5-Fold Cross-Validation.

The notebook also includes:

- Accuracy comparison
- Classification metrics
- Confusion matrices
- Comparison of model performance across folds

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
Diabetes_Prediction_Machine_Learning.ipynb
README.md
