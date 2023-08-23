# credit-risk-calssification

## Overview of the Analysis

The analysis was about loans and their viableness. The purpose was to be able to identify high-risk and healthy loans. In order to achieve this we first look at the `loan_status` column as a standout. To use machine learning I followed the process of:
* Reading the csv
* Splitting it into 2 new Dataframes by the `loan_status` column
* Checking the values based on `loan_status`
* Split the data into training and testing datasets
* Fit a model by using the training data
* Assign the predictions to saved variables
* Evaluate the models

## Results

**Logsitic Regression Model 1:**
* Precision: 95% (100% low-risk and 85% high-risk)
* Accuracy: 99%
* Recall: 95%

**Logistic Regression Model 2:**
* Precision: 99% (100% low-risk and 84% high-risk)
* Accuracy: 99%
* Recall: 96%

## Summary

The 2nd model has a higher balanced accuracy score however both models fail to be able to determine with high precision high-risk laons.
