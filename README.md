# Customer Churn Prediction using Logistic Regression
Overview
This project involves predicting customer churn using a dataset containing various customer features, such as credit score, geography, gender, age, tenure, balance, and more. The goal is to classify whether a customer will churn (leave the company) or not based on these attributes using Logistic Regression.

### Dataset
The dataset used in this project is Churn_Modelling.csv and contains the following columns:

RowNumber: Row identifier

CustomerId: Unique identifier for each customer

Surname: Customer's surname (not used for prediction)

CreditScore: Credit score of the customer

Geography: The country where the customer resides (e.g., France, Spain, Germany)

Gender: The gender of the customer

Age: The age of the customer

Tenure: The number of years the customer has been with the company

Balance: The account balance of the customer

NumOfProducts: The number of products the customer has with the company

HasCrCard: Whether the customer has a credit card with the company

IsActiveMember: Whether the customer is an active member of the company

EstimatedSalary: The estimated salary of the customer

Churned: The target variable, indicating if the customer has churned (1) or not (0)

### Approach
Data Preprocessing:

Load the dataset.

Handle missing values (if any).

Encode categorical features like Geography and Gender using one-hot encoding or label encoding.

Split the data into training and test sets.

Feature Engineering:

Drop unnecessary columns like RowNumber, CustomerId, and Surname which do not contribute to the prediction.

Normalize or scale features if necessary.

### Model Building:

Use Logistic Regression to build the model.

Train the model on the training dataset.


### Dependencies
Python 3.x

Pandas

Numpy

Scikit-learn

Matplotlib

Seaborn
