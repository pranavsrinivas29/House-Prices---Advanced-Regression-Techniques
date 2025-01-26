# House-Prices---Advanced-Regression-Techniques

This is a kaggle competition to predict house prices.

## Problem Description
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## Methodology

Before diving into modellingm, a detailed feature engineering process is made. Firstly NaN values were filled with forward filling then followed by backward filling. Then made a correlation analysis among the variables as there were a lot of predictors involved. Before correlation test, Categorical variables were converted into numerical feature using OneHot Encoding. Feature importance is made considering two scenarios a) Correlativity of features with target variables b) Correlativity between other predictors. Finaaly XGBoost model is trained which serves as a base model, then made Bayesian Hyperparameters Optimization.

XGBoost - It is a advanced regression techniques. XGBoost, which stands for Extreme Gradient Boosting, is a scalable, distributed gradient-boosted decision tree (GBDT) machine learning library. It provides parallel tree boosting and is the leading machine learning library for regression, classification, and ranking problems.

## Conclusions 
Obtained a good MSE and R2 score for the model. 

## About competition
To know more about competition follow this link
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

To view my submission:
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/submissions
