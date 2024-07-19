# 🏡 Predicting Housing Prices with Advanced Regression Techniques! 🏡

## Overview

This project focuses on predicting housing prices using advanced regression techniques. The aim is to develop a model that accurately estimates house prices based on various features such as the number of bathrooms, bedrooms, and area.

## Project Overview

### Data Preparation

- **Dataset**: `HOUSING.CSV`
  - **Features**:
    - `bathrooms`
    - `bedrooms`
    - `area`
  - **Target**:
    - `price`
- **Preprocessing**:
  - Scaled features using `StandardScaler` to standardize the data.
  - Applied `PolynomialFeatures` to capture non-linear relationships between features.

### Model Training and Evaluation

- **Data Splitting**:
  - Split the dataset into training (80%) and testing (20%) sets.
- **Model**:
  - Used **Ridge Regression** to handle potential overfitting and improve model performance.
- **Evaluation**:
  - Evaluated model performance using cross-validation and metrics including Mean Squared Error (MSE) and R^2 Score.

### Performance Metrics

- **Cross-Validated Mean Squared Error**: Provides insight into the model’s performance across different subsets of data.
- **Mean Squared Error (MSE)**: Assesses the accuracy of the model’s predictions on the test set.
- **R^2 Score**: Measures the proportion of variance in the target variable that is predictable from the features.

### Predictive Insights

- Used the trained model to predict housing prices for new data points, providing insights into price estimation based on various features.

## Key Outcomes

- Achieved robust performance metrics with the Ridge Regression model, demonstrating its effectiveness in predicting housing prices.
- Successfully implemented feature scaling and polynomial features to enhance model accuracy.

## Installation

To run the code, you will need the following Python packages:

```bash
pip install pandas scikit-learn
