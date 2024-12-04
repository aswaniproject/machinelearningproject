# machinelearningproject

### Car Price Prediction in the American Market

# Project Overview
This project aims to predict car prices in the American market using machine learning models. The analysis is tailored for a Chinese automobile company entering the US market, helping them understand pricing dynamics and the factors influencing car prices. The results can guide design, manufacturing, and business strategies to stay competitive.

# Data Set
The dataset contains detailed information about cars, including features like engine size, horsepower, weight, and more. It was sourced from a consulting firm's market survey.
Key Details:
Rows: 205
Features: 26
Target: price (dependent variable)

# Project Workflow
Exploratory Data Analysis (EDA):
Analyzed feature relationships using heatmaps and scatter plots.
Identified strong correlations with price (e.g., engine size, horsepower).

Data Preprocessing:
Handled missing values and encoded categorical variables.
Scaled features for algorithms requiring normalization.

Model Implementation:
Built and evaluated the following regression models:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor

Model Evaluation:
Compared models using metrics: R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
Visualized performance with Actual vs Predicted and residual plots.

Feature Importance Analysis:
Identified key predictors for car prices.
Engine size, horsepower, and curb weight were found to be the most significant.

Hyperparameter Tuning:
Improved Random Forest and Gradient Boosting models using GridSearchCV.
Achieved better accuracy and reduced error rates.
Results Summary

Best-Performing Model:
Random Forest Regressor:
R²: 0.92
MSE: 2500
MAE: 35

Key Features Affecting Price:
Engine size
Horsepower
Curb weight

# Insights:
Tree-based models outperform linear models by capturing non-linear relationships in the data.

