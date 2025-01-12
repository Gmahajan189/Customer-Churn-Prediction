# Customer-Churn-Prediction

Project Overview
In this project, a classification model was trained to predict customer churn. The dataset used contains features such as customer demographics, transaction history, and engagement metrics. The primary goal was to build a reliable model that can distinguish between customers who will churn and those who will stay.

Data Description
The dataset contains customer information with the following key features:

Customer ID: Unique identifier for each customer.
Demographics: Age, gender, location, etc.
Engagement Metrics: Usage patterns, customer support interactions, etc.
Churn: A binary target variable indicating whether the customer has churned (1) or not (0).

Modeling Approach
Data Preprocessing: The data was cleaned and preprocessed by handling missing values, encoding categorical variables, and scaling numerical features.
Feature Engineering: Additional features were created from the raw data, such as interaction terms, aggregated customer activity metrics, and transformations to capture hidden patterns and improve model accuracy.
Model Selection: Various machine learning models were experimented with, including Random Forest (RF), LightGBM, Support Vector Classifier (SVC), Logistic Regression, and Neural Networks.
SMOTE: Synthetic Minority Over-sampling Technique (SMOTE) was used to handle class imbalance by generating synthetic examples of the minority class (churn customers).
Hyperparameter Tuning: Several hyperparameter tuning methods were applied to optimize the model performance.
