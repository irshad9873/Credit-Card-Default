# Credit-Card-Default
AlmaBetter Verified Project

# Problem Statement

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments.

# Dataset

We used the [Credit Card Default payment in Taiwan] (https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients) to predict whether the credit card holders are defaulters or Non-defaulters. The Dataset and its attributes are described below

ID: ID of each client

LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit

SEX: Gender (1=male, 2=female)

EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)

MARRIAGE: Marital status (1=married, 2=single, 3=others)

AGE: Age in years

PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months,8=payment delay for eight months, 9=payment delay for nine months and above)

PAY_2: Repayment status in August, 2005 (scale same as above)

PAY_3: Repayment status in July, 2005 (scale same as above)

PAY_4: Repayment status in June, 2005 (scale same as above)

PAY_5: Repayment status in May, 2005 (scale same as above)

PAY_6: Repayment status in April, 2005 (scale same as above)

BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)

BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)

BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)

BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)

BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)

BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)

PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)

PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)

PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)

PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)

PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)

PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)

default.payment.next.month: Default payment (1=yes, 0=no)

# Appraoch Pipeline

Data Preprocessing

Data Exploration

Model Prediction

# Project Files Description

[Credit-Card-Default-Prediction]https://github.com/anas084464/Credit-Card-Default-Prediction/blob/main/Copy_of_Credit_Card_Default_Prediction_Capstone_Project.ipynb) - Includes Exploratory Data Analysis and all algorithms which are used in this project.

[credit card default prediction.pdf ]https://github.com/irshad9873/Credit-Card-Default/blob/main/CapstoneProjectTemplate-210213-230632%20(1).pptx Includes pdf of the presentation of the project.

# 📋 Execution Instruction

The order of execution of the colab notebook is as follows:

1) Credit_Card_Default_Prediction_Capstone_Project.ipynb

First, click on the open in colab button present on the top center of the notebook.

In this .ipynb file, we have -

• EDA on credit card default prediction.

• Handling class imbalance

• Fitting different models and cross validate them.

2) Kaggle Dataset

Downlaod the dataset from kaggle through provided link.Then, connect to the runtime and execute the cell to mount the drive or upload the data file to the current runtime.

3) Cell Path

Finally, delete the path in the dataset loading cell and replace it with the path of your current data file. Run each cell to see the output below it.

# Algorithms

1.XG Boosting
2.Gradient Boosting
3.Support Vector Machine
4.Random Forest Classifier
5.Decision Tree Classifier
6.Logistic Regression

# Conclusions

Majority of the defaulters are those who have credit limit balance between 20,000 to 3,00,000. It might mean that credit card might be too easy to be issued for people who have low credit scores. The variance of the default rate for limit balance over 500,000 NTD is higher than other range of limit balance. It is lower default rate for cardholders have higher education level. Moreover, the default rate for clients whose age over 60 was higher than mid age and young people. The best fit algorithm for predicting limit balance is bagging approach. 
Experimented while creating various model combination with different techniques and achieved accuracy score of random forest is 82.6%. Using a Random Forest classifier, we can predict with ~82.6%. accuracy,
whether a customer is likely to default next month..

# References

Using SMOTE - https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/

XGBoost Documentation - https://xgboost.readthedocs.io/en/stable/

SVM - https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html





