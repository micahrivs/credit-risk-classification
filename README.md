# Credit Risk Classification
In this project, we aim to employ various techniques to build, train, and evaluate a model for credit risk classification. The primary objective is to develop a model capable of assessing the creditworthiness of borrowers based on historical lending activity data obtained from a peer-to-peer lending services company.

## Instructions
This project consists of the following steps:

### 1. Splitting the Data into Training and Testing Sets
- Open the credit_risk_classification.ipynb notebook provided in this repository.
- Load the lending_data.csv dataset from the "Resources" folder into a Pandas DataFrame.
- Construct the labels set (y) based on the values in the "loan_status" column. Create the features DataFrame (X) using the remaining columns.
- Note: A value of 0 in the "loan_status" column represents a healthy loan, while a value of 1 indicates a high risk of default.
- Divide the data into training and testing datasets using the train_test_split function from the sklearn.model_selection module.
### 2. Creating a Logistic Regression Model with the Original Data
- Apply your knowledge of logistic regression within the credit_risk_classification.ipynb notebook to perform the following tasks:
- Fit a logistic regression model using the training data (X_train and y_train).
- Generate predictions for the testing data labels by employing the testing feature data (X_test) along with the trained model.
- Evaluate the model’s performance through the following steps:
- Create a confusion matrix.
- Print a classification report.
- Address the following question: How effectively does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
### 3. Writing a Credit Risk Analysis Report
- Incorporate a concise report that encompasses a summary and analysis of the machine learning models used in this project. Compile this report as the README.md file within your GitHub repository. Organize your report as follows:

Overview of the Analysis: Clarify the purpose and objectives of this analysis.
Results: Describe the accuracy score, precision score, and recall score of the machine learning model using bullet points.
Summary: Summarize the outcomes of the machine learning model. Provide your rationale for recommending the model for adoption by the company. If you do not recommend the model, elucidate your reasoning.
Feel free to expand on these sections as needed to provide a comprehensive and insightful analysis of your credit risk classification project.

License
This project is licensed under the MIT License.

For more details and code implementation, please refer to the credit_risk_classification.ipynb notebook provided in this repository.
