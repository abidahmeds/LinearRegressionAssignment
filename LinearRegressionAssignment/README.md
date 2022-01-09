# Linear Regression Assignment - Bike Sharing Rental Data Analysis 
> Usecase is to understand the factors on which the demand for the shared bikes depends. Specifically to understand the factors affecting the demand for these shared bikes in the American market. The assignment is to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
nBased on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


## Table of Contents
* [General Info](#general-information)
* [AI/ML algorithm/model Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project is about building a Linear Regression model through analysis of multiple parameters affecting the bike sharing rental count and sales of a bike sharing company baed on 2 years [ 2018-2019] data of the sales and related independant parameters data gathered on those days such as environment factors and weather conditions and details such whether the rental ws registered pr casual rent , whether the day was a holiday or working day , which day etc.
- The background of the project is that it is a learning assignment for the Upgrad executive program course on ML/AI.  
- refer the dataset folder , to observe the 730 records data set about bike sharing rental details for each day from 01-01-2018 to 31-12-2019.


## Conclusions
1 Inferences of the Exploratory Data analysis on the dataset.
 * temp and atemp seems to have a obvious liner positive regression relationship
 * windspeed and hum have some relationship but not looking obviously linear
 * weathersit and season have a relationship as in some categories have higher rental count
 * temp,atemp,year have highest correlation with rental count numbers
 * season has a decent correlation with rental count numbers
 * rest seems to be very meekly correlated
 * There is clear year on year increase rental count and sales from 2018 to 2019 , probably this might have continued if there was no covid impact , yet to be seen since there is no 2020,2021 data
 * There is more rental on non-holiday and count of rentals is high for registered users Vs casual users on weekdays , clearly indicating possibility of more office going or day scholar population using bike during weekdays and nonholidays.
 * There is comparatively more rental on summer and spring season , decreases in fall and least in winter.
 * Relative to season , There is comparatively more rental on April to Aug/sep timeframe compared to colder months.
 * More people tend to use bike rentals on clear sky m sunny and cloudy days compared to rainy or snowy days. There is none usage in 2 years on heavy snow or heavy rain day which is no surprise.   
2 Model coeefficients and summary parameters of the final selected model. 
3 Useful charts and plots for the analysis done.


## Technologies Used
- Exploratory Data Analysis on different data set columns , their correlation with each other and rental count
- Build Multi regression models based on relevant independant variables against rental count and compare model summary parameters , p values of coefficients of vairables, r squared / ajusted r squared valuaes and VIF values against each other.


## Contact
Created by [@abidahmeds] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
