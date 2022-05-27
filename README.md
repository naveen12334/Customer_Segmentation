# CUSTOMER SEGMENTATION
Creating a segment's of some customers from a bank based on their credit card details and divide them into some groups through clustering algorithms and then
making a prediction on those groups for new customer's.

# Objective  :
This case requires to develop a customer segmentation to give recommendations like saving plans, loans, wealth management, etc. on target customer groups.
<img align="center" src="https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png" alt="image">

# Input Values
![](https://github.com/naveen12334/Customer_Segmentation/blob/main/Input.PNG)

![](https://github.com/naveen12334/Customer_Segmentation/blob/main/Input2.PNG)

# Result
![](https://github.com/naveen12334/Customer_Segmentation/blob/main/Final.PNG)

# Problem Statement:
Not all customers are same. To know which group is your customer and their
preferences is a big part for success in your business. Unsupervised machine learning
can help marketers to know their audience globally and engage them with their products
accordingly.
Here we can classify millions of people’s interests through their social media activity
and also through other surveys online & offline and cluster them in specific group of
their interest.

# Data Description : 
The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

# Data :  
Use the below link to download the Data Set:[here](https://github.com/pik1989/MarketSegmentation/blob/main/Clustered_Customer_Data.csv)

# Project Various Steps:
# Data Exploration
I started exploring datasets using pandas, NumPy,matplotlib and seaborn.

# Data visualization:
Ploted colleration matrix to get insights about dependend and independed variables. Made chats like( Bocxplot,countplot,distplot,pairplot).

# Model Selection:
K-Means+ clustering algorithm is used for creating segments and
Made many classifiers models like Logistic Regression,RandomForestClassifier,DecisionTreeClassifier,LGBM classifier but selected LIGHT GBM Classifier.

# Hyperparameter Optimization:
Using Randomizedsearch CV and GridSearch CV to select the best parameter for training the model

# Model Dump:
As per selected trained model is dumped to pickled format for app development

# Framework:
App is created on STREAMLIT framework

# Model Accuracy: 
96%

# Deployment:
https://customersegmnt.herokuapp.com/

