# Banking-Customer-Churn-Prediction-
This repository contains a dataset and code for predicting bank customer churn using basic Artificial Neural Network (ANN) modeling and visualizing churn rates in Power BI.

# Dataset Description:
The dataset used in this project is the Bank Customer Churn dataset, containing the following columns:
CustomerId: Contains random values and does not affect customers leaving the bank.
Surname: The surname of a customer has no impact on their decision to leave the bank.
CreditScore: This can affect customer churn since a customer with a higher credit score is less likely to leave the bank.
Country: A customer’s location can affect their decision to leave the bank.
Gender: It’s interesting to explore whether gender plays a role in a customer leaving the bank.
Age: This is certainly relevant since older customers are less likely to leave their bank than younger ones.
Balance: This is also an excellent indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
NumOfProducts: Refers to the number of products a customer has purchased through the bank.
Credit card: Denotes whether or not a customer has a credit card. This column is also relevant since people with credit card are less likely to leave the bank.
ActiveMember: Active customers are less likely to leave the bank.
Churn: Whether or not the customer left the bank.

# Methodology:
Exploratory Data Analysis (EDA): Basic EDA techniques were employed to understand the dataset's characteristics and distributions of features.

Predictive Modeling: A basic Artificial Neural Network (ANN) model was implemented to predict customer churn. The model achieved an accuracy of 79.75%.

Visualization in Power BI: The dataset was utilized in Power BI to visualize the churn rate of the bank by various factors such as gender, activity, location, credit card status, and age group.

# Files:
bank_customer_churn_dataset.csv: The dataset used for analysis.
churn_prediction_ann.ipynb: Jupyter Notebook containing the code for EDA and ANN modeling.
churn_visualization.pbix: Power BI file for visualizing churn rates.
https://github-production-user-asset-6210df.s3.amazonaws.com/42810444/304842896-90c7a65a-bf94-4c39-9c6f-4ee9bce2bb45.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240829%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240829T152543Z&X-Amz-Expires=300&X-Amz-Signature=480394b8788075006db630db7da410ea487c8bdd696ee5995a90b5b6e969e19a&X-Amz-SignedHeaders=host&actor_id=93071272&key_id=0&repo_id=757564551
