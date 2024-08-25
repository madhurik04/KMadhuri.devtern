# Task 1

# House Price Detection

## Overview

This project involves predicting house prices based on various features using machine learning algorithms. The dataset includes features such as the size of the house, number of rooms, and location. The goal is to build a predictive model that can estimate house prices accurately.

## Dataset

- **File:** [HousePriceDetection](https://docs.google.com/spreadsheets/d/1caaR9pT24GNmq3rDQpMiIMJrmiTGarbs/edit?rtpof=true&sd=true&pli=1#gid=1150341366)
- **Features:**
  - `Id`: Unique identifier for each house
  - `MSSubClass`: Identifies the type of dwelling
  - `MSZoning`: The general zoning classification
  - `LotArea`: Lot size in square feet
  - `LotConfig`: Lot configuration
  - `BldgType`: Type of building
  - `OverallCond`: Overall condition rating
  - `YearBuilt`: Original construction year
  - `YearRemodAdd`: Remodel year
  - `Exterior1st`: Exterior covering
  - `BsmtFinSF2`: Basement finished area (square feet)
  - `TotalBsmtSF`: Total basement area (square feet)
  - `SalePrice`: The target variable to predict (price of the house)

## Steps

1. **Data Preparation**
   - Data Loading
   - Data Cleaning
   - Feature Selection
   - Data Splitting

2. **Model Building**
   - Tried various algorithms including Linear Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, and Support Vector Regressor.

3. **Model Evaluation**
   - Evaluated models using Mean Squared Error (MSE) and R-squared metrics.

4. **Best Model**
   - The Gradient Boosting Regressor achieved the best performance with the lowest MSE and highest R-squared.

## Files

- `house_prices.csv`: Dataset
- `house_price_prediction.py`: Script for data processing, feature selection, model training, and evaluation
- `best_model.pkl`: Saved best model (Gradient Boosting Regressor)

## Usage

Run the script `house_price_prediction.py` to execute the data processing, model training, and evaluation. The best model will be saved as `best_model.pkl`.

