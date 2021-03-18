# Telecom_Churn_Prediction_with_Boosting

Customer churn, also known as customer attrition, customer turnover, or customer defection, is the loss of clients or customers. Telephone service companies, Internet service providers, pay-TV companies, insurance firms, and alarm monitoring services, often use customer attrition analysis and customer attrition rates as one of their key business metrics because the cost of retaining an existing customer is far less than acquiring a new one.

Predictive analytics use churn prediction models that predict customer churn by assessing their propensity of risk to churn. Since these models generate a small prioritized list of potential defectors, they are effective at focusing customer retention marketing programs on the subset of the customer base who are most vulnerable to churn.

For this project, we will be exploring the dataset of a telecom company and try to predict the customer churn

Problem Statement
Using the method of Boosting, classify whether or not the customer will churn

About the Dataset
The snapshot of the dataset you will be working on

dataset

A zipped file containing the following items is given:

train.csv
The data file train.csv contains the 5634 instances with the 21 features including the target feature.

test.csv
The datafile test.csv contains the 1409instances with the 20 features excluding the target feature.

sample_submission.csv
Explained under the Submission sub-heading

Telecom Churn Prediction_Data_Dictionary.csv
The file contains data dictionary(Dictionary explaining what each feature of the dataset means) of the Insurance Claim dataset

Telecom Churn Prediction_Student_Template.ipynb
A template notebook explaining the task breakdown to solve the given problem statement (Learners are recommended to use it)

Submission
After training the model on train.csv data, the learner has to predict the target feature of the test.csv data using the trained model. The learner has to then submit a CSV file with the predicted feature.

Sample submission file(sample_submission.csv) is given to you as a reference to the format expected when you submit

Evaluation metrics
For this particular dataset, we are using accuracy_score as the evaluation metric.

Submissions will be evaluated based on accuracy_score as per the below threshold.

Your accuracy_score score	Points earned for the Task
0.795 <= accuracy_score	100% of the available points
0.77 <= accuracy_score < 0.795	80% of the available points
0.75 < accuracy_score < 0.77	70% of the available points
accuracy_score <= 0.75	No points earned
Why solve this project?
After completing this project, you will have a better understanding of how to build a boosting model. In this project, you will apply the following concepts.

Handling missing values in data
Applying AdaBoost
Applying XGBoost
Interpreting evaluation metrics
Skills Covered:
data cleaning
GBM
Xgboost
