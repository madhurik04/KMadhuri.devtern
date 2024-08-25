# Machine Learning Internship at Devtern

This repository contains all the files related to the Machine Learning Internship at Devtern. The tasks covered in this internship include building predictive models, data processing, and feature engineering across different datasets. Below is a brief overview of each project completed during the internship, including what was done and the results achieved.

## Projects

### 1. House Price Prediction

#### Overview
This project involves predicting house prices based on various features using machine learning algorithms. The dataset includes information such as the size of the house, number of rooms, and location. The goal was to build a model that accurately estimates house prices.

#### Dataset
- **Source:** [House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- **Key Features:**
  - `Id`, `MSSubClass`, `MSZoning`, `LotArea`, `LotConfig`, `BldgType`, `OverallCond`, `YearBuilt`, `YearRemodAdd`, `Exterior1st`, `BsmtFinSF2`, `TotalBsmtSF`, `SalePrice`

#### What Was Done
1. **Data Loading**: Loaded the dataset into a Pandas DataFrame.
2. **Data Cleaning**: Handled missing values, encoded categorical variables, and removed duplicates.
3. **Feature Selection**: Selected relevant features for model training.
4. **Model Building**: Implemented and evaluated Linear Regression.
5. **Model Evaluation**: Compared models using Mean Squared Error (MSE) and R-squared metrics.

#### Results
- **Best Model**: Linear Regression
  - **Mean Squared Error**: 1,310,612,221.60
  - **R-squared**: 0.83

### 2. Spam Detection

#### Overview
This project focuses on classifying emails as spam or ham (non-spam) using machine learning techniques. The dataset includes features derived from email text, and the goal was to build an effective spam filter.

#### Dataset
- **Source:** [Spam Mails Dataset](https://www.kaggle.com/datasets/venky73/spam-mails-dataset)
- **Key Features:**
  - `Unnamed: 0`, `label`, `text`, `label_num`

#### What Was Done
1. **Data Loading**: Loaded the dataset and examined its structure.
2. **Data Cleaning**: Removed special symbols and irrelevant information from email texts.
3. **Feature Extraction**: Created features from the email text for model training.
4. **Model Building**: Implemented Logistic Regression model.
5. **Model Evaluation**: Assessed models using accuracy, precision, recall, and F1-score metrics.

#### Results
- **Best Model**: Logistic Regression
  - **Accuracy**: 98.5%
  - **Precision**: 98.7%
  - **Recall**: 98.3%
  - **F1-score**: 98.5%

### 3. Heart Disease Prediction

#### Overview
This project aims to predict the presence of heart disease based on various medical features. The dataset includes information such as age, sex, and various medical indicators. The goal was to develop a predictive model to assist in early diagnosis.

#### Dataset
- **Source:** [Heart Disease Prediction Dataset](https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction)
- **Key Features:**
  - `Age`, `Sex`, `Chest pain type`, `BP`, `Cholesterol`, `FBS over 120`, `EKG results`, `Max HR`, `Exercise angina`, `ST depression`, `Slope of ST`, `Number of vessels fluro`, `Thallium`, `Heart Disease`

#### What Was Done
1. **Data Loading**: Loaded the dataset and reviewed its structure.
2. **Data Cleaning**: Handled missing values and encoded categorical variables.
3. **Feature Selection**: Selected important features based on correlation analysis.
4. **Model Building**: Implemented Logistic Regression model.
5. **Model Evaluation**: Evaluated models using accuracy, precision, recall, F1-score, and confusion matrix.

#### Results
- **Best Model**: Logistic Regression
  - **Accuracy**: 85%
  - **Precision**: 84%
  - **Recall**: 86%
  - **F1-score**: 85%

## Files

- Each project contains its own script for data processing, model training, and evaluation.
- Models and datasets are included where applicable, and scripts are designed to be executed independently.

Feel free to explore the scripts and datasets to understand the methodology and results of each project. For more details, refer to the respective project folders.
