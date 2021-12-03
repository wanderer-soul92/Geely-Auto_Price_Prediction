# Geely-Auto_Price_Prediction

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. 

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

* Which variables are significant in predicting the price of a car
* How well those variables describe the price of a car
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the Americal market. 


## Business Goals 

We are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Steps Involved 

I tried to approch problem with two seprate starategy - 

1. Linear Regression Model with Recurrent Feature elimination with VIF 
* To identify the corelations betwen various independed features and eliminating them to find best fitting/governing variables
* Standrization and One-hot Encoding to make data suitable for ML algorithms 
* RFE with VIF to eliminate corelated variables
* Final model prediction and Test validation 

2. All Regression model comparision 
* Main Aim of this exercise to understand the behaviour and output of different regression ML algorithms ex- Gradient Boost Regressor, L2 Regressor, XG Boost 
* Box-cox conversion is used to normalize the numerical data distribution 
* All model build and comaparison 
* Grid search on top performing models to stablize and fine tunning of the models for better accuracy .


# Note - 
A humble request to the people who came here in search of code for this project, please don't copy the whole code and content. You have spent some time learning this subject. So, better try to write your code in your own way. It will further enhance your skills. If stucked somewhere, this repository is always here to help you.


