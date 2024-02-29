# Module 12 Report Template

## Overview of the Analysis

* The purpose of this credit risk analysis is to predict loan risk based on historical lending data from a peer to peer lending company by splitting the data into training and testing sets and creating a logistical regression model with the original data.
* The financial information we are looking at contains information on loans inidicating their status, healthy=0 and unhealthy=1, meaning there is a higher risk of default. 
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy- the ratio of correctly predicted instances to the total instances.
  The accuracy score of the logistic regression model is 0.99 indicating that it correctly predicts loan outcomes for 99% of cases and is 99% accurate in it's predictions.
  * Precision- ratio of true positive to sum of true positive and negative
    Healthy Loans had a precision of 1.00 meaning that among the loans predicted as healthy and low risk, all of them actually were low risk
    High Risk Loans had a precision of 0.87 meaning that among the high risk loans, 87% are actually high risk

  * Recall Score- ratio of true positives to the sume of true positive and false negatives
    Healthy Loans had a recall score of 1.00 meaning the model correctly identifies all healthy loans
    High Risk Loans had a recall score 0.95 meaning that model correctly identifies 95% of high risk loans, so it has a low false negatrive rate suggesting it is effectively capturing a high amount of high risk loans.

## Summary


This model performs very well with high precision and recall. This is particularily true in the healthy loans class.  There is slightly lowere precision in the high risk loans, but that is to be expected in an imbalanced data set such as this. This model has excellent at identifying risk and could be used with confidence. I would however want their to be a human componant to this analysis, as there are always extenuating circumstances that should be considered. 

