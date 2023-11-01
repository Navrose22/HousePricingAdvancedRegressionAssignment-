# HousePricingAdvancedRegressionAssignment-
> Business Problem:A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
> The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.


## Table of Contents
* [Business Goal](#BusinessGoal)
* [Data](#Data)
* [ModelEvaluation](#ModelEvaluation)
* [Technologies Used](#TechnologiesUsed)

## BusinessGoal
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Data
### Data Sources
- Data set provided by the US based housing company

### Data Understanding
### Data Cleaning
### Exploratory Data Analysis(EDA)
### Data Preparation
- It involves feature engineering.
### Ridge Regression
### Lasso Regression
### RFE on bothe the models


## ModelEvaluation
The model shows that there are some variables that are highly relevant to the sales price. Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house. The higher values of positive coeeficients suggest a high sale value. Some of those features are:
- GrLivArea
- OverallQual
- OverallCond
- TotalBsmtSF
- GarageArea

## TechnologiesUsed
- python:  3.10.9
- numpy:  1.23.5
- pandas:  1.5.3
- matplotlib:  3.7.0
- seaborn:  0.12.2
- sklearn:  1.2.1
- statsmodels:  0.13.5
- scipy:  1.10.0
