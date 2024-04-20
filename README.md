# credit-risk-classification
Module 20


Below is a fundamental summary of the credit risk analysis conducted:

The objective of this task is to develop and assess machine learning algorithms for loan risk assessment. This task employs a dataset containing historical loan transactions from a peer-to-peer lending platform to construct a model capable of identifying borrower creditworthiness and categorizing credit risk forecasts.

The focal financial metric in the dataset is loan status. Key financial attributes utilized to anticipate loan status include loan amount, interest rate, borrower income, debt-to-income ratio, account count, derogatory marks, and total debt.

The loan_status target has two predictive variables. The initial set (with a count of 77,036) signifies healthy loans (assigned '0'), while the second set (count of 2,500) represents loans at high risk of default (assigned '1').

The machine learning procedure for this analysis includes the following steps:

Prepare label sets and feature DataFrame from the provided dataset.
Segregate the dataset into training and testing subsets using the train_test_split method.
Develop a LogisticRegression model and fit the original data into this model.
Generate predictions on the testing dataset labels using the fitted model and testing feature data.
Assess the model's efficacy by computing accuracy scores, confusion matrices, and a classification report.
