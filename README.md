For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers.
These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.
In this case study, you will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans.


Automatic Ticket Classification Case Study



Table of Content

Introduction
Understanding Problem Statement
Business Goal
Business Objectives
Importing all the Libraries
Data Loading
Data preparation
Text Preprocessing
Data Cleaning and Manipulation
Data Lemmatizer
Data POS Tag Extraction
Exploratory data analysis {EDA}
Finding the Top Unigrams,Bigrams and Trigrams
Feature Extraction
Topic Modelling
Finding the best number of clusters
Applying the best number to create word clusters
Inspecting & validate the correction of each cluster wrt the complaints
Correcting the labels if needed
Map the clusters to topics/cluster names
Model training and evaluation
Preprocessing for model
Reverse topic names mapping for supervised learning
X - Y split
Train Test Split
Logistic regression, Decision Tree & Random Forest
Custom Classification Report
Stratified KFold Cross Validation
Custom Grid Search Cross Validation
Multinomial Naive Bayes Classification
Logistic Regression Classification
Decision Tree Classification
Random Forest Classification
Hyper parameter tuning with GridSearchCV
Multinomial Naive Bayes with GridSearchCV
Logistic Regression with GridSearchCV
Decision Tree Classification with GridSearchCV
Random Forest Classifier with GridSearchCV
Model inference



Introduction
In this case study, we have created models that can automatically classify customer complaints based on the products and services that the ticket mentions.



Understanding Problem Statement

For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers.

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

In this case study, you will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans.



Business goal
We need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

You will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, you need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

Credit card / Prepaid card

Bank account services

Theft/Dispute reporting

Mortgages/loans

Others 

With the help of topic modelling, you will be able to map each ticket onto its respective department/category. You can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.
