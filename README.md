# Loan Prediction Application Using Logistic Regression and Machine Learning
 * By: Vasanta Prayaga, Fenny Patel, Luis Hernandez, Ali Saghafi, Parisa Charkhgary
 

![Loan](https://github.com/fennypatel02/Project-4/blob/main/templates/loanpre-thumbnail.png)


## Presentation :

Our Tableau Overview presentation is [Loan Prediction](https://public.tableau.com/app/profile/parisa.charkhgary/viz/LoanPrediction_16628356042020/LoanPrediction)

### Content

A loan application is used by borrowers to apply for a loan. Through the loan application, borrowers reveal key details about their finances to the lender. The loan application is crucial to determining whether the lender will grant the request for funds or credit.

## Introduction 
We analyzed data and built models based on several factors to help predict customer loan eligibility. We trained the models and tested to see which was the most efficient and accurate model to be used for our predictions.

For the purpose of this project we tried Logistic Regression, Random Forest Classifier, K-Neighbors Classifier, Naive Bayes classifier (Multinomial NB), Naive Bayes classifier (Gaussian NB), and Decision Tree Classifier.

Logistic Regression Model gave us highest accuracy and has been chosen for making predictions for this project.
Further application was developed to automate the loan eligibility process in real time based on the information provided by the customer applying for a loan.

# Data 

## About the Data
The dataset contains information about Loan Applicants. There are 12 independent columns and 1 dependent column. This dataset includes attributes like Loan ID, gender, if the loan applicant is married or not, the level of education, applicant’s income etc. 

To load the training data in your jupyter notebook, use the below command:

import pandas as pd
```
loan_data  = pd.read_csv("https://raw.githubusercontent.com/dphi-official/Datasets/master/Loan_Data/loan_train.csv" )
```

## Data Description

* Loan_ID: A unique ID assigned to every loan applicant
* Gender: Gender of the applicant (Male, Female)
* Married: The marital status of the applicant (Yes, No)
* Dependents: No. of people dependent on the applicant (0,1,2,3+)
* Education: Education level of the applicant (Graduated, Not Graduated)
* Self_Employed: If the applicant is self-employed or not (Yes, No)
* ApplicantIncome: The amount of income the applicant earns
* CoapplicantIncome: The amount of income the co-applicant earns
* LoanAmount: The amount of loan the applicant has requested for
* Loan_Amount_Term: The  no. of days over which the loan will be paid
* Credit_History: A record of a borrower's responsible repayment of debts (1- has all debts paid, 0- not paid)
* Property_Area : The type of location where the applicant’s property lies (Rural, Semiurban, Urban)


## Target:

* Loan_Status: Eligible for Loan or not (Y, N)
