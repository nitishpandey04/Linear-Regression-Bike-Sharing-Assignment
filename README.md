# Predicting sharing bikes demand in US market after Covid-19 pandemic
> Using linear regression to make an interpretable model to understand the demand dynamics of shared bikes

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. To make better decisions on scaling their business, the company wants to know the demand of bikes after the pandemic ends. The company has gathered a large dataset on daily bike demands across the American market based on some factors. The company wants to know:-
1. Which variable are significant in predicting the demand for shared bikes i.e. model should be interpretable
2. How well those variables describe the bike demands

The model will be used to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 

The dataset that is being used can be found [here](https://drive.google.com/drive/folders/1rRl5ZahhC23KI-_P_NuXFm83P0vPzDp3?usp=sharing)

### Steps
1. Data Preparation
2. Exploratory Data Analysis
3. Creating dummy variables for categorical variables
4. Train test split and Normalization
5. Model Building
6. Residual Analysis
7. Evaluation

### Model Building Approach
1. Train the model with all the available data using statsmodels
2. Check the p-values and vif scores of variables
3. Drop the variable based on the above two parameters
4. Keep dropping till you achieve a robust model which does not have multicollinearity and there's no extra variable

## Observations
According to the model analysis, three most significant variables are:-
1. temp(+)
2. yr(+)
3. weathersit_light_rain(+)

## Conclusion
- people tend to use bikes when it is relatively hot
- the popularity of the company is growing with time
- when there is rain, less people tend to use bikes.

## Technologies Used
- python 
- numpy
- pandas
- matplotlib
- seaborn
- statsmodels
- sklearn

## Acknowledgements
- This project was based on Linear Regression Assignment from IIITB

## Contact
Created by [@nitishpandey04] - feel free to contact me!
