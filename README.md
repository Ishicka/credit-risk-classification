# credit-risk-classification


## Overview of the Analysis

The purpose of this analysis was to develop a machine learning model for credit risk assessment based on historical lending data. The dataset contained various financial attributes of loans, such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The goal was to predict the likelihood of a loan default, with the focus on distinguishing between healthy loans (labeled as 0) and high-risk loans (labeled as 1).

The stages of the machine learning process included:

Data preprocessing: Handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
Model training: Utilizing logistic regression, a popular algorithm for binary classification tasks, to train the predictive model.
Model evaluation: Assessing the performance of the trained model using metrics such as accuracy, precision, and recall.


## Results
### Logistic Regression Model:
Accuracy Score: 0.99
Precision Score (0 - Healthy Loan): 1.00
Precision Score (1 - High-Risk Loan): 0.86
Recall Score (0 - Healthy Loan): 1.00
Recall Score (1 - High-Risk Loan): 0.91

## Summary
The logistic regression model performed exceptionally well in predicting both healthy and high-risk loans. It achieved near-perfect accuracy for healthy loans and strong performance for high-risk loans, with high precision and recall scores. This model is recommended for credit risk assessment, as it effectively distinguishes between different loan statuses and provides valuable insights for risk management.

In summary, the logistic regression model appears to perform best among the models evaluated. Its performance is robust and well-balanced, making it suitable for various credit risk assessment tasks. However, it's essential to consider the specific problem and priorities when choosing a model, as the importance of predicting healthy or high-risk loans may vary depending on the context.
