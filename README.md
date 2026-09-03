# Credit Risk Prediction
Data Science Master's: Machine Learning Models and Algorithms module project - Credit risk prediction for credit card issuance.  

You have been hired by Pro National Bank as a data scientist, and your first task is to build a model capable of estimating customers' creditworthiness, in order to help the dedicated team understand whether to accept or reject credit card applications.  

## Data provided
You are given anonymized data of customers who have already obtained a credit card and are regularly paying their installments. The data is available in the CSV file [credit_scoring.csv](https://proai-datasets.s3.eu-west-3.amazonaws.com/credit_scoring.csv).  
The file contains information about account holders who applied for a credit line. 

### Dataset columns
- ID: customer identification number  
- CODE_GENDER: customer's gender  
- FLAGOWNCAR: indicator of car ownership  
- FLAGOWNREALTY: indicator of home ownership  
- CNT_CHILDREN: number of children  
- AMTINCOMETOTAL: annual income  
- NAMEINCOMETYPE: type of income  
- NAMEEDUCATIONTYPE: education level  
- NAMEFAMILYSTATUS: marital status  
- NAMEHOUSINGTYPE: type of housing  
- DAYS_BIRTH: number of days elapsed since birth  
- DAYS_EMPLOYED:  number of days elapsed since the hiring date (if positive, it indicates the number of days since becoming unemployed)  
- FLAG_MOBIL: indicator of having a mobile phone number  
- FLAGWORKPHONE: indicator of having a work phone number  
- FLAG_PHONE: indicator of having a phone number 
- FLAG_EMAIL: indicator of having an email address  
- OCCUPATION_TYPE: type of occupation  
- CNTFAMMEMBERS: number of family members  
- TARGET: variable equal to 1 if the customer has a high credit reliability (consistent installment payments), 0 otherwise.

## Objective
You need to build a model that predicts the given target, namely the TARGET variable, which indicates whether the customer has good creditworthiness.  

## Bonus point
If a customer is denied the credit card, the team must be able to provide them with a reason. This means your model must provide easily interpretable indications.
