# Phase-3-Project
Phase 3 project at Flatiron 
## Customer Churn Prediction Project

## Overview
The goal of this project is to build a classifier to predict potential churning customers and suggest recommendations to keep the customers.

## Business Problem
SyriaTel is a national cell phone serivce provider that has a churn rate of 15%. Compared to the national annual average that is over double the amount. I propose to (1)find out what are the biggest factors in the data set that contribute to customer churn (2) How I can use the data set with multiple types of predictive models to give the best reccomendation to get closest to the national average of 7% churn rate.

Stakeholder: SyriaTel


## Data Understanding
This project utilises data from the Churn in Telecom dataset from Kaggle.
The target variable in this dataset that we aimed to predict was identified as the churn column.The features of this dataset include locational information (state and area_code) as well as plan details such as call minutes, charges, customer services calls and whether the customer had an international plan and/or voice mail plan. Our model iterations utilised subsets of these features as well as aggregations of these features to determine which features would best predict cusomter churn.

## Models Used
- Decisioin Tree Classifier
- Logistic Regression Classifier
- KNN Classifier
- Random Forest Classifer
- Gradient Boost Classifer
Evaluated my models on the bases of recall and accuracy. Recall minimizes overfitting and False Negatives whihc is essential to understanding the data. 

## Results and Reccommendations
The best model was the random forest classifier since it had the best recall and accuracy score using the given parameters. This model produced a 95% accuracy score along with a 73% recall value. 4% were false negatives which was the lowest for all 4 models. 

## Future Investigations and Recommendations
-Look into the major issues being reported to customer service to figure out the best way to correct those issues.
-Investigate international plans since over 42% stay
-Find out why the customers who utilize over 55 minutes per day discontinue the service.


