Telecom Churn Classification


Telecom Churn

Overview


This GitHub repository contains the code and documentation for a Telecom Churn Classification project. The goal of this project is to predict customer churn in a telecom company using various classification algorithms. Customer churn is a critical issue for telecom companies, as retaining customers is often more cost-effective than acquiring new ones. By accurately identifying customers at risk of churning, telecom companies can take proactive measures to retain them.

Table of Contents
Introduction
Dataset
Installation
Usage
Algorithms
Results
Contributing
License
Introduction
Telecom churn refers to the phenomenon where customers switch from one telecom service provider to another or completely disconnect from the service. This project aims to build a predictive model that can identify potential churners based on historical customer data. The primary objective is to reduce customer churn by providing insights and actionable recommendations to the telecom company.

Dataset
The dataset used for this project can be found in the data directory. It contains the following columns:

customer_id: Unique identifier for each customer.
gender: Customer's gender.
senior_citizen: Whether the customer is a senior citizen (1) or not (0).
partner: Whether the customer has a partner (Yes/No).
dependents: Whether the customer has dependents (Yes/No).
tenure: Number of months the customer has stayed with the company.
phone_service: Whether the customer has a phone service (Yes/No).
multiple_lines: Whether the customer has multiple lines (Yes/No).
internet_service: Type of internet service (DSL, Fiber optic, No).
online_security: Whether the customer has online security (Yes/No).
online_backup: Whether the customer has online backup (Yes/No).
device_protection: Whether the customer has device protection (Yes/No).
tech_support: Whether the customer has tech support (Yes/No).
streaming_tv: Whether the customer has streaming TV (Yes/No).
streaming_movies: Whether the customer has streaming movies (Yes/No).
contract: Type of contract (Month-to-month, One year, Two year).
paperless_billing: Whether the customer has paperless billing (Yes/No).
payment_method: Payment method (Electronic check, Mailed check, Bank transfer, Credit card).
monthly_charges: Monthly charges for the customer.
total_charges: Total charges incurred by the customer.
churn: Whether the customer churned (Yes/No).



Algorithms
The following classification algorithms were used to build predictive models:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Gradient-Boosting Classifier
The performance of each algorithm is evaluated using various metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

Results
The results of the classification models are presented in the Jupyter notebook. Each algorithm's performance is compared, and the best-performing model is identified. Additionally, insights into which features contribute most to churn prediction are discussed.

Contributing
Contributions to this project are welcome! If you have ideas for improvement, please open an issue or submit a pull request. You can also reach out to the project maintainers for any questions or suggestions.
