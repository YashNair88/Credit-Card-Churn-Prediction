# Credit-Card-Default-Prediction

# Dataset

The UCI Machine Learning Repository Credit Card Dataset contains information on credit card customers in Taiwan from April to September. The dataset includes demographic information, credit information, and payment history information for 30,000 credit card customers. The dataset has 25 features, which are described below:

ID: ID of each customer

LIMIT_BAL: Credit limit of the customer

SEX: Gender of the customer (1 = male, 2 = female)

EDUCATION: Education level of the customer (1 = graduate school, 2 = university, 3 = high school, 4 = others)

MARRIAGE: Marital status of the customer (1 = married, 2 = single, 3 = others) AGE: Age of the customer

PAY_0: Repayment status in September (-2 = no consumption, -1 = paid in full, 0 = use of revolving credit, 1 = payment delay for one month, 2 = payment delay for two months, …, 8 = payment delay for eight months or more)

PAY_2: Repayment status in August (same scale as PAY_0)

PAY_3: Repayment status in July (same scale as PAY_0)

PAY_4: Repayment status in June (same scale as PAY_0)

PAY_5: Repayment status in May (same scale as PAY_0)

PAY_6: Repayment status in April (same scale as PAY_0)

BILL_AMT1: Amount of bill statement in September

BILL_AMT2: Amount of bill statement in August

BILL_AMT3: Amount of bill statement in July

BILL_AMT4: Amount of bill statement in June

BILL_AMT5: Amount of bill statement in May

BILL_AMT6: Amount of bill statement in April

PAY_AMT1: Amount paid in September

PAY_AMT2: Amount paid in August

PAY_AMT3: Amount paid in July

PAY_AMT4: Amount paid in June

PAY_AMT5: Amount paid in May

PAY_AMT6: Amount paid in April

default payment next month: Whether or not the customer defaulted in the next month (1 = yes, 0 = no)

The goal of the dataset is to predict whether a customer will default on their credit card payment in the next month, based on their demographic information, credit information, and payment history.

# Churn Prediction

To perform churn prediction on the Credit Card Default Payment dataset in Taiwan, we can use various machine learning algorithms such as logistic regression, decision trees, and random forests. These algorithms can be used to build a predictive model that identifies the factors contributing to churn and predicts the likelihood of a customer churning.

# Preprocessing

We use Robust Scaler for preprocessing which involves cleaning the data, handling missing values, and transforming the data into a format suitable for predictive modeling. We then use feature selection, where we identify the most important variables that contribute to churn.

#  Machine Learning Model

Once the data is preprocessed and the variables are selected, we can train our machine learning model on the dataset. The model learns to identify patterns in the data and make predictions based on those patterns. The model's accuracy can be assessed using various performance metrics such as accuracy, precision, and recall.

