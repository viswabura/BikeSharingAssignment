# Bike Sharing Assignment

Building a Linear Regression model to identify the significant variables in predicting the demand for shared bikes

## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information

This is an assignment in which we use Python to build a Linear Regression model to understand BoomBikes - a US bike-sharing provider.

In this project, we need to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.


## Conclusions

Those are the conclusions retrieved from the model, further information can be found in the Notebook

After our final model, we can see the top predictor variables:
 - **Temperature** temp has a coefficient value of 0.4258, which indicates that it is a strong predictor variable influence the shared bike demand
 - **Year** yr has a coefficient value of 0.2357, that means the demand for shared bike will increase as year increase
 - **Weather** weathersit_snow has a coefficient value of -0.2434, which indicates that if it a snow day that will affect the booking of shared bikes
 - **Windspeed** has a coefficient value of -0.1519, indicates that strong wind will affect the booking of shared bikes


## Technologies Used

- python - version 3.12.4
- pandas - version 2.2.2
- notebook - version 7.0.8
- matplotlib - version 3.8.4
- seaborn - version 0.13.2
- scikit-learn - version 1.4.2
- statsmodels - version 0.14.2

## Contact

Created by [@viswabura] - feel free to contact me!