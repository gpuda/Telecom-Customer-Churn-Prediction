Telecom Customer Churn Prediction

Problem statement: Based on all information from this data set, a model was made to predict whether a particular customer will churn or not.

During the model development, data set was separated in train (70% of data) and test(30% of data) data.
On the train data, a model was build that calculates which attributes are significantly related to churn (eg. 'tenure - Contract Duration', 'PhoneService', 'PaperlessBilling', 'TotalCharges', OnlineBackup', 'TechSupport'..).
When model was applied on the test data, Churn was predicted with an accuracy of 78%

Source: Kaggle
This data set contains the following data with following features:

churn_data.csv
    'customerID'
    'tenure'
    'PhoneService'
    'PaperlessBilling'
    'PaymentMethod'
    'MonthlyCharges'
    'TotalCharges'
    'Churn'
customer_data.csv
    'customerID'
    'gender'
    'SeniorCitizen'
    'Partner'
    'Dependents'
internet_data.csv
    'customerID'
    'MultipleLines'
    'InternetService'
    'OnlineSecurity'
    'OnlineBackup'
    'DeviceProtection'
    'TechSupport'
    'StreamingTV'
    'StreamingMovies'
