# Eligibility of Loan Prediction
Eligibility of loan prediction using Decision Tree and Ensemble Methods

## Introduction
Loan eligibility prediction is the estimation of the tendency of the customer whether they are eligible to take the loan as per their status and properties.

## Problem Statement
The problem statement of loan eligibility prediction is to develop a machine learning model that can accurately predict whether a loan applicant is eligible for a loan based on various factors such as income, employment history, property, salary, and other relevant financial and personal information.

## Objectives
1. To implement an algorithm to predict the customers who are eligible to take loans from financial institutions
2. To compare multiple machine learning models and choose the best model from them.
3. To provide transparency to the loan eligibility system.

## Scope
This project will be helpful to banks and other financial institutions. Financial institutions can analyze or review historical data before giving a loan to a customer. The historical data of customers will be used in order to do analysis. Later on, some analysis will also be done to find the factors that affect the prediction result the most. It can be used by e-commerce companies to offer financing options to customers for buying products.

## Dataset
The dataset is taken from Kaggle and belongs to a Hackathon organized by “Univ.AI”!! <br>  This dataset contains information regarding the people who are eligible for loans or not. <br> It includes features like income, age, profession, experience, etc. All the features are listed below.<br><br>
Number of instances: 280000<br>
Number of features: 11 Input Features and 1 Target Feature (Defaulted).

Attribute Information: <br>
The detailed information of each attribute is listed as:<br><br>
Income – Income of the user.<br><br>
Age – Age of the user.<br><br>
Experience – Professional experience of the user in years.<br><br>
Married/Single – Whether married or single.<br><br>
House_Ownership – Owned or rented or neither.<br><br>
Car_Ownership – Does a person own a car?<br><br>
Profession – Profession.<br><br>
City – City of Residence.<br><br>
State – State of Residence.<br><br>
Current_Job_Yrs – Years of experience in the current job.<br><br>
Current_House_Yrs – Number of years in a current residence.<br><br>
Defaulted – Defaulted on a loan.<br><br>

## Data Preprocessing
The pre-processing and cleaning of the dataset will be an important step in the project to ensure data quality and consistency.<br>
It involves the following steps:<br>
•	Data Cleaning: This involves removing or correcting missing, incorrect, or irrelevant data from the dataset.<br>
•	Data Integration: In some cases, you may need to combine data from multiple sources. This step involves merging datasets that have different formats, structures, or variables.<br>
•	Data Transformation: This step involves converting data from one format to another, such as scaling numerical data or transforming categorical data to numerical values.<br>
•	Data Reduction: Sometimes, datasets can be too large or complex to work with. This step involves reducing the size or complexity of the data, such as by selecting a subset of features or observations.<br>
•	Data Discretization: This step involves transforming continuous data into discrete data, such as binning or grouping data into categories.<br>
•	Data Normalization: This step involves scaling the values of features to have a similar range, which can improve the performance of some machine learning algorithms.<br>
•	Feature Engineering: This step involves creating new features from existing ones, which can improve the performance of some machine learning algorithms.<br>
<br><br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/dp1.png)<br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/dp2.png)

## Model Training
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/mt1.png)<br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/mt2.png)<br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/mt3.png)<br>

## Decision Tree Algorithm
A decision tree is a tree of decisions where the complex problem is divided into several small problems and solving them.<br>
It is a graphical representation of a series of decisions or choices that lead to a final outcome. <br>
Each decision or choice is represented by a node, and the branches represent the possible outcomes<br><br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/dat1.png)<br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/dat2.png)<br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/dat3.png)<br>

## Random Forest
A random forest is a combination of decision trees to improve the overall performance. There are various ways to combine decisions from multiple models. One such way is voting. Voting is used for classification. For example, if we have three models that can classify whether an animal is a fish or not. Of five models, if three or more classify the animal as Fish, the animal is likely a fish. Another technique for combining the decisions from multiple models in an ensemble is averaging which is used for regression problems.
A depth unlimited decision tree or deep decision tree is a strong learner. It easily overfits the training data. The random forests’ main goal is to combine multiple overfitted decision trees to reduce variance or overfitting. Random forest is a bagging method so it uses bootstrap samples to train each decision tree. It introduces additional randomness by considering only a random subset of features to determine the best split at each node. This additional randomness reduces the correlation between the individual decision trees, which in turn reduces the variance even further.<br>

![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/ra1.png)<br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/ra2.png)<br>

## AdaBoost
AdaBoost, also known as adaptive boosting is a popular boosting algorithm in the ensemble method. Boosting algorithms train a weak model on initial data with equal weight. For the wrong prediction, it increases the weight and then trains the model. It repeats this process until the specified number of models is trained and combines the final result. AdaBoost uses a decision tree with single depth (decision tree with single split) which is also known as a decision stump.<br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/ad1.png)<br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/ad2.png)<br>
![](https://github.com/SunTam/EligibilityofLoanPrediction/blob/main/images/ad3.png)<br>

## Conclusion
By analyzing customer information such as income, age, experience, ownership, profession, city, and state, institutions can use these models to make informed decisions about approving or denying loan applications.<br> These models can also help to identify high-risk applicants who may default on their loans and take appropriate measures to minimize losses. 




