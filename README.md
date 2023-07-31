# credit-risk-classification
In this project, we will be using various techniques to train and evaluate a model for credit risk classification. The goal is to build a model that can identify the creditworthiness of borrowers based on historical lending activity data from a peer-to-peer lending services company.

## Instructions
The instructions for this Challenge are divided into the following subsections:

## Split the Data into Training and Testing Sets
- Open the credit_risk_classification.ipynb notebook provided and use it to complete the following steps:
- Read the lending_data.csv data from the "Resources" folder into a Pandas DataFrame.
- Create the labels set (y) from the "loan_status" column and then create the features (X) DataFrame from the remaining columns.
- NOTE: A value of 0 in the "loan_status" column means that the loan is healthy, while a value of 1 means that the loan has a high risk of defaulting.
- Split the data into training and testing datasets using train_test_split from the sklearn.model_selection module.

## Create a Logistic Regression Model with the Original Data
- Use your knowledge of logistic regression to complete the following steps in the credit_risk_classification.ipynb notebook:
- Fit a logistic regression model using the training data (X_train and y_train).
- Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
- Evaluate the model’s performance by doing the following:
- Generate a confusion matrix.
- Print the classification report.
- Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.
Structure your report as follows:
- An overview of the analysis: Explain the purpose of this analysis.
- The results: Using a bulleted list, describe the accuracy score, precision score, and recall score of the machine learning model.
- A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
