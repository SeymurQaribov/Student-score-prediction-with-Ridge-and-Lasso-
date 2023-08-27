# Student-score-prediction-with-Ridge-and-Lasso-
Utilizing Ridge and Lasso regression techniques to elevate the model's performance.
# Linear Regression with Ridge and Lasso
This repository contains a Python script that demonstrates the use of Linear Regression with Ridge and Lasso regularization techniques to predict test scores of students based on various features.

## Introduction
In this script, we start by loading a dataset (`student_marks.csv`) that includes student test scores and other related features. We apply exploratory data analysis, visualize correlations, and create additional features to enhance the model's predictive power.

## Features and Techniques Used
- Data loading using Pandas
- Exploratory Data Analysis (EDA) using Pandas Profiling and Seaborn
- Feature engineering to create new columns
- Linear Regression modeling
- Ridge Regression and Lasso Regression for regularization
- GridSearchCV for hyperparameter tuning
- Visualization of residuals using Seaborn

## Steps
1. Load the dataset `student_marks.csv`.
2. Perform exploratory data analysis using Pandas Profiling and visualize correlations.
3. Create additional features to improve model performance.
4. Split the dataset into training and testing sets.
5. Scale the data using StandardScaler.
6. Train a Linear Regression model and evaluate its performance.
7. Apply Ridge Regression with hyperparameter tuning and evaluate the model.
8. Apply Lasso Regression with hyperparameter tuning and evaluate the model.
9. Visualize residuals for both Ridge and Lasso models.
