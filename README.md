# Telco Customer Churn Prediction

## Overview
This project predicts customer churn in a telecommunications company using a **Random Forest Classifier**. The dataset is preprocessed, balanced using oversampling, and optimized with hyperparameter tuning.

## Dataset
- **Source:** `Telco_Customer_Churn.csv`
- **Target Variable:** `Churn`
- **Features:** Includes `tenure`, `SeniorCitizen`, `MonthlyCharges`, and categorical variables.

## Steps Involved

### 1. Data Preprocessing
- Handling missing values and duplicates
- Encoding categorical variables
- Standardizing numerical features
- Balancing the dataset using `RandomOverSampler`

### 2. Model Training
- Splitting the data into training and testing sets
- Training a `RandomForestClassifier`
- Evaluating performance using:
  - Accuracy
  - Classification report
  - Confusion matrix

### 3. Hyperparameter Tuning
- Using `RandomizedSearchCV` to optimize the **Random Forest** model

## Results
- **Initial Model Accuracy:** **89%**

## Dependencies
Ensure you have the following libraries installed:

```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn

