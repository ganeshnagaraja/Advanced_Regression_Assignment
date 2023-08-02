# Housing Price Predictor

## Overview

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and 
decide whether to invest in them or not.

## Business Goal
Required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. 
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Results

I have performed Lasso and Ridge Regression with varying hyperparameters - Alpha, folds, etc
Obtained R2 and MSE scores on Test set are below:

Ridge Regression:
    The optimum alpha is 1

    The R2 Score of the model on the test dataset for optimum alpha is 0.7517961186497641

    The MSE of the model on the test dataset for optimum alpha is 0.0036756374958161067

Lasso Regression:
    The optimum alpha is 0.0002

    The R2 Score of the model on the test dataset for optimum alpha is 0.7662314016521267
    
    The MSE of the model on the test dataset for optimum alpha is 0.003461866191445042

## Contact
Created by ganeshnagaraja[ganesh_nagaraja@yahoo.in] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->