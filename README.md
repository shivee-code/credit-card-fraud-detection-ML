# credit-card-fraud-detection-ML
<b>This is a Supervised Machine Learning-Project.</b><br><br>
<b>Building a credit card fraud detection model using Logistic Regression Algorithm.</b>
1. Essential Exploratory Data Analysis (EDA)<br>
2. Data Preprocessing</br>


<b>Building a another model using KNN algorithm.</b>
<br>
<b>Building a model using Decision Tree Algorithm.</b>
<br>
<b>Building a model using Random Forest Algorithm.</b>
<br>
<b>Building a model using Support Vector Machine Algorithm.</b>

<b>OBJECTIVE:</b>
<br>
Predict whether a transaction is fraudulent based on various features of the transaction. This is binary classification problem where the target variable is <b>Fraud,</b> indicating whether a transaction is fraudulent (1) or legitimate (0).
<br><br>
<b>DATA DICTIONARY:</b><br>
<b>1. TransactionID:</b> Unique identifier for each transaction (integer).<br>
<b>2. TransactionAmount:</b> Amount of the transaction in USD (float).<br>
<b>3. TransactionTime:</b> Time of the transaction in hours since the first transaction (float).<br>
<b>4. MerchantCategory:</b> Category of the merchant (categorical: 'Retail', 'Online', 'Restaurant', 'Travel').<br>
<b>5. CustomerAge:</b> Age of the customer making the transaction (integer, ranging from 18 to 80).<br>
<b>6. CustomerGender:</b> Gender of the customer (categorical: 'Male', 'Female').<br>
<b>7. CustomerIncome:</b> Annual income of the customer in USD (integer, ranging from 20,000 to 200,000).<br>
<b>8. TransactionLocation:</b> Location where the transaction took place (categorical: 'Urban', 'Suburban', 'Rural').<br>
<b>9. PreviousFraudCount:</b> Number of fraudulent transactions by the customer in the past 6 months (integer, ranging from 0 to 5).<br>
<b>10. Fraud:</b> Target variable indicating whether the transaction is fraudulent (1) or not (0) (binary).<br>
<br>
<b>Model Comparison (summary of accuracies):</b><br>
Logistic Regrassion Accuracy: 75.33%<br>
K-Nearest Neighbors Accuracy: 75.00%<br>
Decision Tree Accuracy: 71.00%<br>
Support Vector Machine Accuracy: 77.00%<br>
<br>
<b>Otimization in Machine learning</b>
<br>
Logistic Regression Best Params: {'C': 0.1, 'max_iter': 100, 'solver': 'lbfgs'
Logistic Regression Best Accuracy: 0.7385714285714287

K-Nearest Neighbors Best Params: {'algorithm': 'auto', 'n_neighbors': 10, 'weights': 'distance'}
K-Nearest Neighbors Best Accuracy: 0.75

Decision Tree Best Params: {'criterion': 'gini', 'max_depth': 5, 'min_samples_leaf': 2, 'min_samples_split': 5}
Decision Tree Best Accuracy: 0.7657142857142858

Random Forest Best Params: {'max_depth': None, 'min_samples_leaf': 2, 'min_samples_split': 2, 'n_estimators': 200}
Random Forest Best Accuracy: 0.7971428571428572

Support Vector Machine Best Params: {'C': 1, 'gamma': 'scale', 'kernel': 'rbf'}
Support Vector Machine Best Accuracy: 0.7485714285714286

