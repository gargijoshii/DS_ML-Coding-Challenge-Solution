# DS_ML-Coding-Challenge-Solution

# Sourcing Cost Prediction with Regression Models

## Overview
This repository contains code for building and evaluating regression models to predict sourcing costs based on a provided dataset. The models are implemented in Python using various machine learning libraries such as scikit-learn, XGBoost, pandas, numpy, matplotlib, and seaborn.

## Dataset
The dataset consists of training and testing data in Excel format (`train.xlsx` and `test.xlsx`, respectively). Initial exploratory data analysis (EDA) is performed to understand the dataset's structure, summary statistics, and the distribution of the target variable (Sourcing Cost).

## Data Preprocessing
Categorical variables in both the training and testing datasets are encoded into numerical form using LabelEncoder to enable machine learning algorithms to process categorical data effectively. Additionally, outliers in the training data are identified and removed using Z-score normalization to ensure model robustness.

## Regression Models
Several regression models are trained on the preprocessed training data, including:
- Random Forest Regressor
- Linear Regression
- Gradient Boosting Regressor
- XGBoost Regressor

## Model Evaluation
The trained models are evaluated using mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE) metrics on the testing data. These metrics provide insights into the models' predictive performance, with lower values indicating better performance.

## Conclusion
Based on the evaluation results, the Random Forest Regressor and XGBoost Regressor models demonstrate the lowest MAE and RMSE values, indicating superior predictive performance compared to other models.


