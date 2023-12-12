# MLR-Bikesharing
> Build a Multi Linear regression model to identify the key predictors which will explain well about the demand of the shared bike.


## Table of Contents
* [General Info](#general-information)
* [Steps followed](#steps-followed)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

## Conclusions
- From the variable ‘season’, we clear see bike demand is low in the ‘spring’ season
and high in the ‘fall’ season.
- From the variable ‘mnth’, we clear see bike demand is high in ‘JUL, AUG, SEP’
comparatively than other months
- From the variable ‘weathersit’, we clear see bike demand is high in ‘Clear’ and low
in ‘Light Snow’.
- From the variable ‘holiday’, we clear see bike demand is low in holidays compare
to working day.

- We can see that the equation of our best fitted line is:
    𝑐𝑛𝑡=0.3374+0.2309×𝑦𝑟+0.4795×𝑡𝑒𝑚𝑝+0.0551×𝑤𝑖𝑛𝑡𝑒𝑟+0.0558×𝑆𝐸𝑃−0.1493×ℎ𝑢𝑚−0.1699×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑−0.1096×𝑠𝑝𝑟𝑖𝑛𝑔−0.0768×𝐽𝑈𝐿−0.2457×𝐿𝑖𝑔ℎ𝑡𝑆𝑛𝑜𝑤−0.0570×𝑀𝑖𝑠𝑡−0.0413×𝑇𝑈𝐸
- Strong Positive predictor are
    temp
    yr
    SEP
    winter


## Technologies Used
- python - version 3.0

# Python library Used
- numpy
- pandas
- matplot
- seaborn
- ploty
- MinMaxScaler
- sklearn.model_selection
- sklearn.preprocessing
- sklearn.feature_selection
- sklearn.linear_model
- statsmodels.api
- statsmodels.stats.outliers_influence
- sklearn.metrics


## Acknowledgements
- This project was inspired by UpGrad.


# Contact
Created by [@PrabakarTS] - feel free to contact me!


