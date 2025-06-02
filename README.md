# customer_churn_prediction
This project focuses on analyzing customer churn data to understand the factors that influence a customer’s decision to leave a telecom company. The dataset contains various customer attributes, account details, and service usage features. The primary goal is to predict customer churn and gain business insights for retention strategies.

📁 Dataset Description
The dataset contains 7,043 records and 21 columns with the following fields:

Column Name	       Description

customerID	       Unique identifier for each customer
gender	           Customer gender: Male or Female
SeniorCitizen	     Indicates if the customer is a senior citizen (1 = Yes, 0 = No)
Partner	           Whether the customer has a partner
Dependents	       Whether the customer has dependents
tenure	           Number of months the customer has stayed with the company
PhoneService	     Indicates if the customer has phone service
MultipleLines      Whether the customer has multiple lines
InternetService	   Type of internet service: DSL, Fiber optic, or None
OnlineSecurity	   Whether the customer has online security service
OnlineBackup	     Whether the customer has online backup service
DeviceProtection   Whether the customer has device protection service
TechSupport	       Whether the customer has tech support service
StreamingTV	       Whether the customer uses streaming TV service
StreamingMovies	   Whether the customer uses streaming movies service
Contract	         Contract type: Month-to-month, One year, Two year
PaperlessBilling	 Indicates if billing is paperless
PaymentMethod	     Payment method used by the customer
MonthlyCharges	   Monthly billing amount
TotalCharges	    Total amount charged to the customer
Churn            	Target variable indicating if the customer has churned (Yes/No)

⚠️ Note: TotalCharges is an object type due to possible non-numeric entries (e.g., blanks or spaces), which may require preprocessing.

📊 Objective
   Perform Exploratory Data Analysis (EDA) to uncover patterns in customer behavior.

   Build predictive models to identify customers likely to churn.

   Provide business insights to reduce churn and improve customer retention.

🛠️ Project Workflow
   1.Data Cleaning

  Handle missing or erroneous values in TotalCharges.

  Convert relevant columns to appropriate data types.

2.Exploratory Data Analysis (EDA)

Univariate and bivariate analysis

Churn rate distribution across customer segments

3.Feature Engineering

Encode categorical variables

Create new derived features if necessary

4.Model Building

Logistic Regression

Random Forest

Simple ANN

Gradient Boosting (XGBoost, LightGBM)

5.Evaluation

Accuracy, Precision, Recall, F1 Score

Confusion Matrix and ROC-AUC Curve

🧰 Tools and Technologies
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook 


