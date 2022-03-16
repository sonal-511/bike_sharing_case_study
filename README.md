# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Building a multiple linear regression model for the prediction of demand for shared bikes

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

cnt = 0.233*const +
        0.102*season_summer + 
        0.149*season_winter + 
        0.053*mnth_aug + 
        0.119*mnth_sept - 
        0.045*weekday_tuesday - 
        0.243*weathersit_Light Snow & Rain - 
        0.058*weathersit_Mist & Cloudy + 
        0.229*yr - 
        0.103*holiday + 
        0.539*temp - 
        0.166*hum - 
        0.182*windspeed '

## Conclusions
- weather conditions play an important role in bike sharing demand
- during summer and winters people rent more bikes hence more focus should be there on expanding businees in these weather conditions
- during light snow or cloudy weather settings company might see a less demand in bikes as its  ha a negative correlation with target variable
- the company should keep expanding its business as when passing year the demands are increaing
- Temperature is a strong indicator for bike share count, it has a high positive coefficent in the regression equation
- Bike rentals are less on holidays

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- sklearn
- statmodel api
- numpy
- matplotlib


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->