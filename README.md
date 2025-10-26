# House_Price_Prediction_Capstone_Project
**🏠 House Price Prediction – Capstone Project**
**Overview**

This project aims to predict house prices using advanced regression models and feature engineering techniques.
The dataset includes property attributes such as living area, number of bedrooms/bathrooms, lot size, quality, and age of the house.
The goal is to build a robust model that can estimate property prices with high accuracy and provide insights into key price-driving factors.

**Objectives**

Perform data cleaning, EDA, and feature transformation to prepare the dataset.
Develop multiple regression models such as Linear Regression, Ridge, Lasso, XGBoost, LightGBM, and CatBoost.
Compare model performance based on R², Adjusted R², and RMSE.
Deliver predictive accuracy improvements and transparent driver insights using SHAP and feature importance plots.

**Methodology**

Exploratory Data Analysis (EDA)
Univariate, bivariate, and multivariate analysis to understand relationships between features and price.
Outlier detection and treatment.

Data Preprocessing
Handling missing values, encoding categorical variables, scaling numerical data.

Model Building
Training multiple regression and ensemble models.
Hyperparameter tuning using GridSearchCV.

Model Evaluation & Validation
Evaluating models using Adjusted R², RMSE, and cross-validation scores.

Interpretability
Feature importance & SHAP analysis for understanding the key price drivers.

**Tech Stack**
Languages: Python

Libraries:
pandas, numpy, matplotlib, seaborn,
scikit-learn, xgboost, lightgbm, catboost, shap

Tools: Jupyter Notebook, VS Code

Visualization: Matplotlib, Seaborn, SHAP plots

**Results & Insights**
Model with the best performance: XGBoost Regressor
Achieved an Adjusted R² of ~0.88, showing strong predictive capability.
Key features influencing price: living_measure, quality, lot_measure, and Age.
SHAP analysis revealed interpretability of feature impacts for what-if analysis.
