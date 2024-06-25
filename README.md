# credit_risk_classification

## Overview of the Analysis

This analysis was completed to describe the precision of healthy loans and high-risk loan predictions with the Logistic Regression model. The data used included loan sizes, interest rate, income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. We focused on loan status to predict. Loan status included two variables: 0 (healthy loan) or 1 (high-risk loan).

## Process
The data was split using the train_test_split method with a random state of 1. No data preprocessing was utilized. The Logistic Regression model was trained and the predictions were created.


## Results

* Logistic Regression:</br>
    * Accuracy was 0.99, a high accuracy score.</br>
    * Precision was 1.00 (a perfect score) for health loans and 0.85 for high-risk loans. Both scores are high. The high-risk loans could improve.</br>
    * Recall was 0.99 for healthy loans and 0.91 for high-risk loans. Both scores are high.</br>

## Summary

The logisitic regression model utilized had high scores in all three areas: accuracy, precision, and recall. Although the best scores were seen for the healthy loans (0), we need to focus on the predictions for the high-risk loans. The high-risk loans need to be inditified so they can be further analyzed for a possible loan to increase business.

There is room to improve on the logistic regression model results for high-risk loan predictions. This model can be used with 88% accuracy on high-risk loans. Other models should be tested to compare results.
