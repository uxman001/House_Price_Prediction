# House_Price_Prediction

## 📌 Project Overview

This project focuses on predicting house prices using various property features such as square footage, number of bedrooms, bathrooms, location, and other housing-related attributes. Machine Learning regression techniques are used to estimate house prices based on historical housing data.

The objective is to build a predictive model that can help buyers, sellers, and real estate professionals make informed decisions regarding property valuation.

## 🎯 Objective

The main goal of this project is to:

Analyze housing market data.
Preprocess and clean the dataset.
Perform feature engineering and encoding.
Train a regression model to predict house prices.
Evaluate model performance using regression metrics.
Visualize actual vs predicted house prices.
## 📊 Dataset

Dataset: House Price Prediction Dataset

The dataset contains information about residential properties, including:

Square Footage (Area)
Number of Bedrooms
Number of Bathrooms
Floors
Location
Year Built
Garage Availability
Property Condition
Sale Price (Target Variable)
## 🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
## 📂 Project Workflow
1. Data Loading
Load the dataset using Pandas.
Inspect the dataset structure.
Check for missing values and duplicates.
2. Data Preprocessing
Handle missing values.
Remove duplicate records.
Encode categorical features such as location.
Scale numerical features when necessary.
3. Exploratory Data Analysis (EDA)
Analyze feature distributions.
Visualize correlations between variables.
Identify important factors affecting house prices.
4. Feature Selection

## Selected features include:

Area (Square Footage)
Bedrooms
Bathrooms
Floors
Location
Garage
House Age

## Target Variable:

Price
## 5. Model Training

Regression models used:

### Linear Regression

A simple and interpretable regression algorithm used as a baseline model.

### Gradient Boosting Regressor

An advanced ensemble learning technique that improves prediction accuracy.

Example:

from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)

## 🔍 Key Findings
Property size (square footage) has a strong impact on house prices.
Location significantly affects property valuation.
Houses with more bedrooms and bathrooms generally have higher prices.
Gradient Boosting often provides better prediction accuracy than Linear Regression.
Proper feature preprocessing improves model performance.


## 📚 Skills Demonstrated
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Regression Modeling
Feature Scaling
Model Evaluation (MAE & RMSE)
Data Visualization
Real Estate Price Analysis

## 👨‍💻 Author

Muhammad Usman