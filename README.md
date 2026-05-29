# Marketing Campaign Response Prediction Using Machine Learning

## Project Overview

This project applies supervised machine learning techniques to predict customer response to marketing campaigns using the Customer Personality Analysis dataset. The study compares multiple classification models to identify the most effective model for customer response prediction and support data-driven marketing decision-making.

## Objectives

* Predict whether customers will respond to marketing campaigns
* Compare the performance of multiple supervised machine learning models
* Identify the most influential factors affecting customer response
* Generate business insights to improve marketing campaign targeting

## Dataset

* Dataset: Customer Personality Analysis Dataset (Kaggle)
* Records: 2,240 rows
* Variables: 29 features
* Target Variable: Response (1 = Responded, 0 = Did Not Respond)

The dataset includes:

* Customer demographics
* Income level
* Purchase behavior
* Marketing campaign history
* Purchase channel activity

## Technologies & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Google Colab

## Data Preprocessing

The following preprocessing techniques were applied:

* Handling missing values
* Removing duplicate records
* Feature engineering
* Feature selection using Random Forest
* One-Hot Encoding
* Feature scaling using StandardScaler
* Train-test split (70:30)

## Feature Engineering

New features created:

* Total_Campaign_Accepted
* Total_Children
* Total_Spend
* Age
* Customer_Days

## Machine Learning Models

The following supervised learning models were developed and evaluated:

1. Logistic Regression
2. Naive Bayes
3. K-Nearest Neighbors (KNN)
4. Decision Tree
5. Random Forest
6. XGBoost

## Evaluation Metrics

Models were evaluated using:

* ROC-AUC
* Accuracy
* Precision
* Recall
* F1-Score

## Results

Logistic Regression achieved the best overall performance:

* ROC-AUC: 0.897
* Accuracy: 0.903
* F1-Score: 0.610

XGBoost also demonstrated competitive performance with similar ROC-AUC results.

## Key Insights

Important predictors of customer response include:

* Recency
* Total Campaign Accepted
* Customer Days
* Total Spend
* Income
* Purchase Activity

The findings suggest that customer behavioral variables are stronger predictors than demographic characteristics.

## Business Impact

This project demonstrates how machine learning can support:

* Better customer targeting
* Reduced marketing costs
* Improved campaign effectiveness
* Data-driven marketing strategies

## Repository Contents

* marketing_campaign_prediction.ipynb
* marketing_campaign.csv
* README.md

## Author

Jasmine Wong Jia Xuan
Business Analytics Undergraduate
Universiti Sains Malaysia (USM)
