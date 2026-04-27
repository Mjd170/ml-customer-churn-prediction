# Customer Churn Prediction – Machine Learning Project

## Overview
This project focuses on predicting customer churn using tabular data.
The objective is to support business decision-making by identifying customers
who are likely to leave and prioritizing retention efforts.

## Problem Context
Customer churn is a critical challenge in banking and subscription-based businesses.
Losing an existing customer is often more costly than acquiring a new one.
This project aims to predict churn in advance to support proactive retention strategies.

## Problem Statement
Given customer demographic and behavioral data, the task is to build a machine
learning model that predicts whether a customer is likely to churn.
The model should focus on minimizing high-cost errors that negatively impact the business.

## Dataset
The dataset contains customer demographic information, account details, and activity indicators,
used to predict whether a customer will churn.
Data preprocessing was applied prior to model training.

## Approach
- Data cleaning and preprocessing of customer demographic and behavioral data
- Feature engineering to capture churn-related patterns
- Training a machine learning model suitable for tabular data
- Model evaluation using confusion matrix and recall-focused metrics

## Evaluation Strategy
Accuracy alone was not sufficient for this problem due to class imbalance.
Recall was prioritized to minimize missed churned customers, as false negatives
represent a higher business cost.
Model performance was analyzed using confusion matrix and appropriate classification metrics.

## Key Insights
- Certain customer behavior patterns strongly correlate with churn.
- Customers with lower activity levels showed higher churn risk.
- Recall optimization helped reduce the number of missed churned customers.
- The model can support targeted customer retention strategies.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

## Project Structure

ml-customer-churn-prediction/
│
├── notebook/
│   └── churn_prediction.ipynb
│
├── data/
│   └── Churn_Modelling.csv
│
└── README.md


## Author
Majed Hawsawi – Applied Machine Learning & Computer Vision Enthusiast (Computer Science Student)




