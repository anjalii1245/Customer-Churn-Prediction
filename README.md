Customer Churn Prediction
## Project Overview
This project aims to predict customer churn for a telecom company using machine learning techniques. Customer churn occurs when customers stop using the service, and accurately predicting churn enables the company to strategize retention efforts and reduce revenue loss.

## Dataset
Dataset: Telco Customer Churn dataset (~7,000 records)

Features include customer demographics, account details, service subscriptions, monthly and total charges, tenure, and churn label.

Data source: Publicly available on Kaggle (link included in the code).

## Key Steps
Data Cleaning and Preprocessing

Removed unnecessary columns

Converted TotalCharges to numeric and handled missing data

Encoded categorical variables and mapped churn to binary

## Exploratory Data Analysis (EDA)

Visualized churn distribution to understand class imbalance

Created a correlation heatmap to find relationships between features

## Model Building

Used Logistic Regression for churn classification

Achieved about 81% accuracy on test data

Evaluated model performance with precision, recall, f1-score, and confusion matrix

## Feature Importance Analysis

Identified major predictors: MonthlyCharges, TotalCharges, tenure, contract type

## Business Insights

Customers with higher monthly costs and short tenure are more likely to churn

Long-term contracts correlate with better retention

Recommendations include targeted retention strategies for high-risk customers

## How to Run
Clone this repository

Install required Python libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Download the Telco Customer Churn dataset and place it in the project folder

Run the Python script or Jupyter notebook for cleaning, EDA, and model training

Visualizations and evaluation metrics will be generated

## Results
Accuracy: 81%

Key visualizations include churn distribution, feature correlation heatmap, and feature importance chart

Provides actionable business insights for reducing churn

## Future Work
Experiment with other classification algorithms like Random Forest, XGBoost

Handle class imbalance using oversampling or undersampling techniques

Develop an interactive dashboard for real-time churn monitoring
