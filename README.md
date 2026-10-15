# Diabetes Prediction Using Machine Learning

## Project Overview

This project aims to predict diabetes outcomes using Machine Learning classification algorithms.

The main objective is to compare different models, evaluate their predictive performance, and identify the most influential features associated with diabetes prediction.

## Dataset

The project uses the Pima Indians Diabetes Dataset, containing **768 observations** and 8 predictive variables, including glucose levels, BMI, age, blood pressure, insulin levels, and number of pregnancies.

The target variable, `Outcome`, indicates whether an observation corresponds to a positive or negative diabetes outcome.

## Methodology

The analysis includes:

- **Exploratory Data Analysis (EDA):** Descriptive statistics, visualizations, correlation analysis, and identification of patterns.
- **Data Preprocessing:** Handling medically implausible zero values, median imputation, outlier analysis, and feature scaling where applicable.
- **Train/Test Split:** 80/20 stratified splitting.
- **Model Training:** Implementation and comparison of classification algorithms.
- **Hyperparameter Optimization:** Grid search with 5-fold cross-validation.
- **Model Evaluation:** Accuracy, Precision, Recall, F1-score, and ROC-AUC.
- **Model Interpretability:** SHAP analysis to identify influential predictors.

## Machine Learning Models

Three classification algorithms were evaluated:

1. Logistic Regression
2. Random Forest
3. Gradient Boosting

## Key Results

Gradient Boosting achieved the strongest initial test-set performance:

- **Accuracy:** 76.0%
- **ROC-AUC:** 83.2%

After hyperparameter optimization, the Gradient Boosting model obtained:

- **Accuracy:** 74.7%
- **ROC-AUC:** 82.1%

The results demonstrate the importance of comparing multiple classification algorithms and evaluating their generalization performance.

## Feature Importance

SHAP analysis identified several influential predictors, particularly:

- Glucose
- BMI
- Age
- Pregnancies

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- SHAP
- Matplotlib / Seaborn
- Google Colab

## Conclusions

This project demonstrates the complete workflow of a supervised Machine Learning classification problem, from exploratory analysis and preprocessing to model optimization, evaluation, and interpretability.

The results highlight the potential of Machine Learning for identifying patterns in health-related datasets. However, the models require additional external validation before any potential clinical application.

## Author

**Juan Cruz Ftulis**

Mathematics Graduate | Data Analytics & Machine Learning
