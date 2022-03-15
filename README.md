# Bike-Sharing-Assignment

# What is BoomBikes ?

- A bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. 
- It allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. 
- This bike can then be returned to another dock belonging to the same system.


# Business objective: 

- The objective is to model the demand for shared bikes with the available independent variables. 
- It will be used by the management to understand how exactly the demands vary with different features. 
- They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
- Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
## Requirements

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands.

## What needs to be done ?

1. Create a linear model that describe the effect of various features on demand.
2. The model should be interpretable so that the management can understand it.


## Business Understanding
- Understand the requirements of the Assignment

## Data Understanding
- Understand the datasets provided

##Data Cleaning and Manipulation
- Clean the data and perform some manipulation

## Data Visualization
- Perform EDA to understand various variables.
- Check the correlation between the variables.

## Data Preparation
- Create dummy variables for all the categorical features.
- Divide the data to train & Test.
- Perform Scaling.
- Divide data into dependent & Independent variables.

## Data Modelling & Evaluation
- Create Linear Regression model using mixed approach (RFE & VIF/p-value).
- Check the various assumptions.
- Check the Adjusted R-Square for both train & Test data.
- Report the final model.

## Technologies Used
- Jupyter Notebooks
- Anaconda Navigator
- Github
- Matplot lib
- Seaborn
- numpy
- pandas
- Statsmodels
- sklearn

# Conclusions
## from EDA Process

- The Bike Sharing Bookings are high during FALL Season.
- The Bike Sharing Bookings are high in the year 2019 and low in 2018.
- The Bike Sharing Bookings are high in the middle of the year (may to oct).
- At start of the year tends to increase and at the end of the year it decreases
- The Bike Sharing Bookings are high in Weekends and holidays
- The Bike Sharing Bookings are high when they slightly moving towards weekends.
- The Bike Sharing Bookings are high in the clear weather compared to mist and light snow

## Model Building and Evaluation
### So The Variables which are significant in predicting the demand for shared bikes

- Year
- Working day
- Temp
- Windspeed
- Sep
- Sat
- Lightsnow
- Mist
- Summer
- Winter

### How well those variables describe the bike demands?

cnt = 0.075 + (year x 0.233) + (workingday x 0.056) + (temp x 0.550) - (windspeed x 0.155) + (sep x 0.097) + (sat x 0.068) - (Light_snowrain x 0.0287) - (Misty x 0.080) + (summer x 0.089) + (winter x 0.131)

### How the model is significant ?

- F - Statistics for the Best Suited Linear Regression Model is 253.0.
- Higher the F - Statistics, the model is more significant
- Also P value is Zero , this also proves the model is more significant.
- Also VIF value for the chosen model is below 5


### Validations of assumptions

- Error terms are normally distributed with mean zero.
- The Probability of distribution of the errors has constant variance. 
- Error values are statistically independent and not depend on any other values.
- Independent variables having linear relationships with the dependent variables

### squared and Adjusted R-squared values for both trained and test datasets

- R-squared:Trained dataset  : 83.5
- R-squared:Test dataset     : 79.6
- Adjusted R-squared:Trained dataset  : 83.17
- Adjusted R-squared:Test dataset     : 78.62

## Acknowledgements
Give credit here.
- This project was inspired by the Bike sharing companies where i came to know the process about how the bike is being shared for a rental purposes.
- Got many references from the internet for the bike sharing terminologies
- Thanks to upgrad on giving me this opportunity to work on this analysis

## Contact
Created by [@naveenharry03] - feel free to contact me! naveenharry03@gmail.com


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
