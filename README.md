# UpGrad Linear Regression Assignment
- The project aims to analyse and model the past data from a US bike-sharing provider, BoomBikes. 
- It will be used by the management to understand how exactly the demands vary with different features. 
- They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
The project is for a bike-sharing company.

Background: <br>
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

Business Probem: <br>
- The bike-sharing company wants to understand the factors affecting the demand for the shared bikes in the American market. The company wants to know:
    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands

Dataset: <br>
- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Conclusions
- ‘season’ is a strong driver variable 
    – maximum bikes are rented in the season 3(fall), followed by 2(summer), 4(winter), 1(spring)
- ‘weathersit’ is a strong driver variable 
    – more bikes are rented in weathersit 1(Clear, Few clouds, Partly cloudy, Partly cloudy), followed by 2(Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist) and 3(Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)
- Even though 'temp' & 'atemp' showed strong correlations with 'cnt', they were not part of the final model
    - This is because most of their variations are explained by features like season and weathersit
- People rented more bikes on an average in the year 1(2019) than year 0(2018)
- People rented more bikes on the months 7,9,6,8 than the other months
    - However, 'mnth' is not part of the final model because most of its variations are explained by features like season
- People rented more bikes on non-holidays than holidays
- ‘weekday’ has little to no effect on the target variable
- ‘workingday’ has little to no effect on the target variable


## Technologies Used
- pandas - version 1.5.0
- numpy - version 1.21.0
- seaborn - version 0.12.0
- sklearn - version 1.1.2
- statsmodels - version 0.12.2

## Contact
Created by [@krishnajiraoh] - feel free to contact me!
