# Pranjal-Srivastava-202501100300186-MLE-CASESTUDY-2
Credit Card Fraud Detection using XGBoost, SMOTE and SVM
# Credit Card Fraud Detection

## Case Study

**Credit Card Fraud Detection using XGBoost with SMOTE, Decision Threshold Optimization and SVM**

## Objective

The primary goal of this project is to build a machine learning system capable of identifying potentially fraudulent credit card transactions. Since fraudulent transactions are much less frequent than normal transactions, special techniques are applied to handle the class imbalance.

## Dataset

The dataset contains credit card transaction information with features including:

* Time
* V1 to V28
* Transaction Amount
* Class

### Target Variable

* **0** – Legitimate transaction
* **1** – Fraudulent transaction

## Methodology

The project is implemented through the following workflow:

1. Load and inspect the transaction dataset.
2. Analyze the distribution of normal and fraudulent transactions.
3. Separate the input features and target variable.
4. Divide the dataset into training and testing sets.
5. Apply **SMOTE** only to the training data to address class imbalance.
6. Train an **XGBoost classifier** on the balanced training dataset.
7. Evaluate the model using a Classification Report and ROC-AUC score.
8. Adjust the prediction threshold to improve fraud detection performance.
9. Examine feature importance to understand which features contribute most to the predictions.
10. Train an **SVM model** as a baseline for comparison.
11. Compare the performance of XGBoost and SVM.

## Machine Learning Models

### XGBoost

XGBoost is used as the primary classification algorithm because it can effectively model complex patterns in transaction data.

### Support Vector Machine (SVM)

SVM is used as a baseline model to provide a comparison with the XGBoost classifier.

## Techniques Applied

* **SMOTE** – Handles the imbalance between legitimate and fraudulent transactions.
* **Decision Threshold Tuning** – Helps control the trade-off between detecting fraud and generating false alarms.
* **Feature Importance Analysis** – Identifies the features that have the greatest influence on the model.
* **ROC-AUC** – Measures how effectively the model separates fraudulent tran
