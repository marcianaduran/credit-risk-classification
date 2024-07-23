# Credit Risk Classification Instructions

Use various techniques to train and evaluate a model based on loan risk. 
Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Steps
1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model with the Original Data
3. Write a Credit Risk Analysis Report

# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to build and evaluate a machine learning model using a logistic regression classification algorithm to predict credit risk. Speficially, the analysis aimed to classify loands as either "healthy" (low risk) or "high risk" based on historical lending activity. Logistic regression was the primary algorightm used in this analysis. It is suitable for binary classification tasks and provides probabilities for class membership.

### Data Attributes (77,536 entries)
* `loan size`
* `interest_rate`
* `borrower_income`
* `debt_to_income`
* `num_of_accounts`
* `derogatory_marks`
* `total_debt`

### ML Process
1. Data loading and exploration
2. Data split into  training and testing sets
3. Train the model
4. Fit the model
5. Test the model
6. Evaluate the accurace of the model

## Results
* Logistic Regression Machine Learning Model:
*                          precision    recall  f1-score   support
        Healthy Loan         1.00      0.99      1.00     18765
        High-risk Loan       0.85      0.91      0.88       619

        accuracy                               0.99     19384
        macro avg          0.92      0.95      0.94     19384
        weighted avg       0.99      0.99      0.99     19384

## Summary
<!--* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )-->
* The logistic regression model performed exceptionally well in predicting healthy loans, with a precision and recall of 1.00 and 0.99 respectively.
* The model also performed well in predicting high-risk loans, with a precision of 0.85 and a recall of 0.91.
* Overall, the model achieved an accuracy of 99%, indicating a high level of correctness in its predictions therefore it is recommended to use this machine learning model to predict credit risk.
