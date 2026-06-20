# House Price Prediction using Machine Learning

## Overview

This project was developed as part of a Machine Learning Internship assignment. The objective is to predict house prices using property features and identify the factors that have the greatest impact on housing prices.

The project covers the complete machine learning workflow including data exploration, preprocessing, model training, evaluation, visualization, and business insights.

---

## Dataset

Dataset Source:

https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

The dataset contains various housing attributes such as:

- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Main Road Access
- Guest Room
- Basement
- Air Conditioning
- Preferred Area
- Furnishing Status

Target Variable:

- Price

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Exploration

- Loaded the dataset using Pandas
- Examined dataset dimensions and structure
- Identified target and feature variables
- Checked for missing values and duplicates

### 2. Data Preprocessing

- Removed duplicate records
- Converted categorical variables using One-Hot Encoding
- Prepared the dataset for machine learning models

### 3. Model Training

Two regression models were implemented:

#### Linear Regression

A baseline regression model used to understand linear relationships between housing features and price.

#### Random Forest Regressor

An ensemble learning model used to capture complex relationships and compare performance against Linear Regression.

---

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Results

| Model | MAE | RMSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 970,043 | 1,324,507 | 0.653 |
| Random Forest | 1,021,546 | 1,400,566 | 0.612 |

Linear Regression achieved the best performance on this dataset.

---

## Visualizations

The project includes:

- Distribution of House Prices
- Correlation Heatmap
- Actual vs Predicted Prices
- Feature Importance Analysis

All generated charts are available in the `charts` folder.

---

## Key Findings

- Area was the most influential factor affecting house prices.
- Bathrooms and parking availability also contributed significantly to property value.
- Linear Regression outperformed Random Forest on this dataset.
- Larger properties with better amenities generally command higher market prices.

---

## Business Recommendation

Real estate agencies should prioritize property size, bathroom count, parking facilities, and premium amenities when estimating property values and designing marketing strategies.

---

## Project Structure
