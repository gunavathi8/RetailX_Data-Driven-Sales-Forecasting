# RetailX: Data-Driven Sales Forecasting

## Overview
This repository contains a Sales Forecasting project aimed at predicting the sales of products in various Retail outlets. The project leverages XGBoost Regressor as the primary model due to its efficiency and accuracy in handling regression tasks. Additionally, LightGBM and CatBoost models were trained to compare their performance with XGBoost.
The goal of this project is to provide insights into sales trends and help Big Mart outlets optimize their inventory and sales strategies.

## Project Objectives
Predict the sales of products in Big Mart outlets based on historical data and product features.
Use XGBoost Regressor as the main model for prediction.
Compare the performance of LightGBM and CatBoost with XGBoost to identify the best-performing model.

## Steps in the Project
  1. Exploratory Data Analysis (EDA):
     1. Analyzed the dataset for missing values, outliers, and feature distributions.
     2. Visualized relationships between features and the target variable.
  2. Data Preprocessing:
     1. Handled missing values and encoded categorical variables.
     2. Scaled numerical features and performed feature engineering to improve model performance.
  3. Modeling:
     1. Trained the XGBoost Regressor as the primary model.
     2. Trained LightGBM and CatBoost models for comparison.
     3. Used hyperparameter tuning (e.g., GridSearchCV) to optimize model performance.
  4. Evaluation:
     1. Evaluated models using metrics like Root Mean Squared Error (RMSE) and R² Score.
     2. Compared the performance of XGBoost, LightGBM, and CatBoost to identify the best model.
    
## Technologies Used
- Programming Language: Python
- Libraries:
   - pandas & numpy: Data manipulation and analysis
   - scikit-learn: Machine learning utilities
   - XGBoost, LightGBM, CatBoost: Gradient boosting models
   - matplotlib & seaborn: Data visualization
