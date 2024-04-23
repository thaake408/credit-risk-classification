# credit-risk-classification
**Module 20**


Credit risk analysis overview:

The objective of this task is to develop and assess machine learning algorithms for loan risk assessment. This task employs a dataset containing historical loan transactions from a peer-to-peer lending platform to construct a model capable of identifying borrower creditworthiness and categorizing credit risk forecasts.

The focal financial metric in the dataset is loan_status. Key financial attributes utilized to anticipate loan status include loan amount, interest rate, borrower income, debt-to-income ratio, account count, derogatory marks, and total debt.

The loan_status target has two predictive variables; The first set with a count of 75,036 which signifies healthy loans (assigned '0'), and a second set with a count of 2,500 that represents loans at high risk (assigned '1').

The machine learning procedure for this analysis includes the following steps:

- Prepare label sets and feature DataFrame from the provided dataset.

- Segregate the dataset into training and testing subsets using the train_test_split method.

- Develop a LogisticRegression model and fit the original data into this model.

- Generate predictions on the testing dataset labels using the fitted model and testing feature data.

- Assess the model's efficacy by computing accuracy scores, confusion matrices, and a classification report.
