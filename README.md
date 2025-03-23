Telco Customer Churn Prediction

Overview

This project aims to predict customer churn in a telecommunications company using a Random Forest Classifier. The dataset is preprocessed, balanced using oversampling, and optimized using hyperparameter tuning.

Dataset

Source: Telco_Customer_Churn.csv

Target Variable: Churn

Features: Includes tenure, SeniorCitizen, MonthlyCharges, and categorical variables.

Steps Involved

Data Preprocessing

Handling missing values and duplicates

Encoding categorical variables

Standardizing numerical features

Balancing the dataset using RandomOverSampler

Model Training

Splitting the data into training and testing sets

Training a RandomForestClassifier

Evaluating performance using accuracy, classification report, and confusion matrix

Hyperparameter Tuning

Using RandomizedSearchCV to optimize the Random Forest model

Results

Initial Model Accuracy: 0.89%


Dependencies

Python

Pandas, NumPy

Scikit-learn

Imbalanced-learn

Matplotlib, Seaborn

