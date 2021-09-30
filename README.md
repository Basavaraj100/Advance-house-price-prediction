# Advance-house-price-prediction

## Problem Statment
Using  Different paramters related to house,we need to predict what will be the selling price of house

## Approach
- First we checked the missing values
- We found the relationships betweeen missing values and target throgh bargraph, hence without dropping missing values we created label as missing in each missing valued categorical features
- For categorical features **Target guided label encoding** done to convert into numerical features


## MOdel building
- We used Polynimial Linear Regression to predict the house price

## Feature selection
- Select from model technique used to select the important features, Lasso regression used to select the important features

## MOdel Performance
- The model is able to explain 91.2% variation in the data i.e r2_score is 91.2%

# Model deployement
- Model is deployed in Local machine using Streamlit





















Selling price of house depends on how old the house is, area of the house and other features. We built a regression model to predict the elling price of the house by using such relevent features. Relevent features are selected by using feature importance from decision tree model. All Categorical features are encoded by using target giuded lebel encoding

key skills: EDA, Feature importance, Decision tree, Multiple linear regression
