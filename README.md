# Boom Bikes Demand Prediction
>The case study aims at building a Multivariate Linear Regression (MLR) model for predicting demand on
> a given day using historical data of 2 years. The modelling focuses on identifying the key factors and their corresponding 
> contribution to the demand of bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A bike-sharing system is a service in which bikes are made available for 
shared use to individuals on a short term basis for a price or free.
- Modelling demand for shared bikes with the available independent variables 
which will be used by the management to understand how exactly the demands vary with different features.
- Analysis uses statsmodel library for model preparation and its statistical analysis.
- RFE Recursive Feature Elimination is extensively used for identifying key features.

### Assumption
- Multivariable Linear regression applicability over the use-case.

## Conclusions
- Subjective question have been added as pdf file.
- BoomBikes MLR Results: 
  - | Variables | R2          |  Adj R2 | Test R2 | p-value (p<5%) | VIF<5 |
    | ----------- | ----------- |---------|---------|----------------|------|
    | 7         | 0.809       |   0.806 |0.81   |  True          |True |
  
  - | Features | Coefficients|
    | ----------- | ----------- |
    |atemp|0.4593|
    |season_spring|-0.1562|
    |mnth_july|-0.0964|
    |hum|-0.1683|
    |weathersit_snow|-0.1740|
    |windspeed|-0.1156|
    |yr|0.2344|
 
   
  


## Technologies Used
- Pandas - version 1.2.4
- Numpy - version 1.20.1
- matplotlib - version 3.3.4
- seaborn - version 0.11.1
- statsmodels - version 0.12.2
- scikit-learn  - version 0.24.1
- LibreOffice - version 7.2.3


## Contact
Created by [@santokhsdg] - feel free to contact me!
