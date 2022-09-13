# Project: Bank Marketing Campaigns for Term Deposits

## Problem Formulation
This data set contains records relevant to a direct marketing campaign of a Portuguese banking institution.Our client is a retail banking institution. Term deposits are a major source of income for a bank. A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term. The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing and digital marketing. Telephonic marketing campaigns still remain one of the most effective way to reach out to people. However, they require huge investment as large call centers are hired to actually execute these campaigns. Hence, it is crucial to identify the customers most likely to convert beforehand so that they can be specifically targeted via call.

We are provided with the client data such as age of the client, their job type, their marital status, etc. Along with the client data, you are also provided with the information of the call such as the duration of the call, day and month of the call, etc.

This is the classic marketing bank dataset uploaded originally in the UCI Machine Learning Repository.

(Sourse of the data : https://archive.ics.uci.edu/ml/datasets/bank+marketing).

Number of Instances: 41188

Number of Attributes: 21

## Problem Statement
Leverage the given data set to build an End-to-End Data Science Project and Predict whether a customer is subscribing the term deposit or not.

## Hypothesis Generation
This is one of the important stages in any Data Science/Machine Learning pipeline. It involves understanding the problem in detail by brainstorming as many factors as possible which can impact the outcome. It is done by understanding the problem statement thoroughly and before looking at the data.

Below are some of the factors which I think can highly affect the people who choose term deposits :

* Age: Mostly elder people doesn't take risk so they might prefer term deposits over any other.

* Income: Income of a person increases as he/she gains experience and thus, people with higher age tend to have higher income for the same occupation. Higher income people might interested in investing.

* Occupation: People working in 'Tech-support', 'Sales' & 'Exec-managerial' will surely have good salary and they might consider investing more than other people.

* Marital Status: People who are married tend to invest more than unmarried people

## Steps to follow
It is a Binary Classification Problem

General Overview: Have a General Overview of the data

* ##### EDA: Perform Exploratory Data Analysis(EDA) to gain more clear insights of the data
* ##### Data Preprocessing: With the information gained after performing EDA, Preprocess the Data accordingly
* ##### Model Building: Once the data is properly cleaned and preprocessed, use this data to build a Machine Learning
* ##### Hyperparameter Tuning: Tune the Hyperparameters of the best performing model
* ##### Model Performance: Assess the Performance of the Model on the Testing data set
* ##### Save the model: Save the Best Performing Model
* ##### Predictions: Make Predictions on the Testing data set
