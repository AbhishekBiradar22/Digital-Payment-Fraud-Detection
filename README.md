# Digital-Payment-Fraud-Detection

# Overview  
Digital payment fraud is a significant concern in today's digital world. Digital payment systems have helped a lot in the ease of payments But at the same time it increased in payment frauds. Digital payment frauds can happen with anyone using any payment system, especially while making payments using a credit card. That is why detecting Digital payment fraud is very important. 

# Objective 
This project aims to develop a fraud detection system using machine learning algorithms. 

# 1. Data Collection: 
Dataset Columns: 
 step: represents a unit of time where 1 step equals 1 hour. 
 type: type of online transaction. 
 amount: the amount of the transaction. 
 nameOrig: customer starting the transaction. 
 oldbalanceOrg: balance before the transaction. 
 newbalanceOrig: balance after the transaction. 
 nameDest: recipient of the transaction. 
 oldbalanceDest: initial balance of recipient before the transaction. 
 newbalanceDest: the new balance of recipient after the transaction. 
 isFraud: fraud transaction.

# 2. Data Preprocessing: 
1. Data Cleaning: Identify Null Values: Begin by identifying columns or 
features with Null values. 
2. Handling Outliers: Check any outliers present or not using box plot. 
3. Standardiza on: Scale numerical features to a standard range (e.g., 0-1)  
4. Encoding: Apply one hot encoding to Convert categorical variables into a 
binary format, creating separate columns for each category. 
5. Feature Engineering: Create new features that might be more predictive 
or meaningful for the model (e.g. nameOrig, nameDest).
 
# 3. Exploratory Data Analysis (EDA): 
Exploratory Data Analysis or EDA is used to take insights from the data. Data Scientists and Analysts try to find different patterns, relations and anomalies in the data using some statistical graphs and 
other visualization techniques. 

# 4. Algorithms :
![accuracy](https://github.com/user-attachments/assets/f90ebfb5-8dd8-4014-bd14-3883a31820ed)





