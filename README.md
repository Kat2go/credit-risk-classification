# Module 20 Credit Risk Classification Models
# Overview of the Analysis

* The purpose of this analysis is identify the creditworthiness of borrowers based on historical lending activity.

* The lending data provided loan size, interest rates, borrowers income, debt to income ratio, number of accounts, derogatory marks, total debt, and loan status.

* Objective of analysis was to predict if loans were healthy or high-risk.

* The stages of machine learning process
    - Split into training and testing datasets
    - Predictions of the test were compared to the given data
    - Due to imbalance of given data did a resampled training dataset by using RandomOverSampler from imbalanced-learn
    - New logistic regression model was fit to the resampled data
    - Then predictions of the resampled data were compared to the given results

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: 94.42%
  * Precision:
    * Healthy Loans: 100% 
    * High-Risk Loans: 87% 
  * Recall:
    * Healthy Loans: 100%
    * High-Risk Loans: 89% 


* Machine Learning Model 2:
  * Accuracy: 99.60%
  * Precision:
    * Healthy Loans: 100% 
    * High-Risk Loans: 87%
  * Recall:
    * Healthy Loans: 100% 
    * High-Risk Loans: 100% 

## Summary
* Accuracy of both healthy('0') and High-Risk('1') loans is higher with Machine Learning Model 2.  
* Recall is also 100% for both '0' and '1' for with Model 2.  
* Precision is an issue with high-risk loans in both models.
* Model 2 would be the recommended Model to use.  
