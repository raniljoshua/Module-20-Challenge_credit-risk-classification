# Module-20-Challenge_credit-risk-classification

## Overview of the Analysis

The purpose of this analysis was to use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. In this case, I was trying to predict the 'loan_status' variable for healthy loans versus high-risk loans. For this machine-learning process, I separated the data into labels and features, checked the balance of the target values, split the data into training and testing datasets, and then created a logistic regression model using the training data and evaluated the model's performance on its predictions.

## Results

The balanced accuracy scores, and precision and recall scores, of the different machine learning models are as follows:

* Machine Learning Model 1 (using Original Data):
  * The logistic regression model (using the original imbalanced data) predicts the labels well based on the balanced accuracy score of 94.4%. According to the classification report, the model's predictions for `0` (healthy loan) had a precision of 100% and recall of 100%, while for `1` (high-risk loan) had a precision of 87% and recall of 89%.



* Machine Learning Model 2 (using Oversampled Data):
  * The logistic regression model (using the oversampled data) predicts the labels even better based on the balanced accuracy score of 99.6%. According to the classification report, the model's predictions for `0` (healthy loan) had a precision of 100% and recall of 100%, while for `1` (high-risk loan) had a precision of 87% and recall of 100%.

## Summary

The second machine learning model (using the oversampled data) seems to perform the best since it has a higher balanced accuracy score. In addition, the resampled data used for this model has an equal number of data points for the labels, resulting in better precision and recall scores in the classification report.
