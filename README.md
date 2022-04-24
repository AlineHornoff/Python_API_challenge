# Python_API_challenge

## What's the weather like in your part of the world and is it possible to pick a hotel based on your ideal weather?

In this Bootcamp Project the answers to these questions are explored exploring the use of API keys and JSON traversals. Each of the answers are given utilising visulisations via scatter plots, linear regression plots and heatmaps. 


## Contents

### WeatherPy

Under utilisation of OpenWeatherMap API, Python requests and JSON traversals the following scatter plots and linear regressions showcase the below relationships for 500+ randomly chosen City from around the world:

#### Scatter Plots

* Latitude vs Temperature(C)
* Latitude vs Humidity(%)
* Latitude vs Cloudiness(%)
* Latitude vs Wind Speed(kph)

#### Summary
Latitude specifies the north–south position of a point on the Earth's surface geographically. Latitude is an angle which ranges from 0° at the Equator to 90° at the poles.

The Latitude vs Temperature plot indicates the closer a city is to the Equator the higher the temperature. Whereas the closer the city is to either of the poles the lower the temperature in comparison to cities close to the Equator.

The Latitude vs Humidity plot indicates that a larger part of cities has a humidity of above 50%.

Latitude vs Cloudiness plot does not indicate any strong relationships.

Latitude vs Wind speed plot indicates that the majority of cities has a wind speed of between 0 to 8 kph.

#### Linear Regressions

* Northern Hemisphere - Temperature (C) vs. Latitude
* Southern Hemisphere - Temperature (C) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (kph) vs. Latitude
* Southern Hemisphere - Wind Speed (kph) vs. Latitude

#### Summary
A strong relationship negative between latitude and maximum temperature can be observed in the Northern Hemisphere plot. The plot indicates as the latitide increases the maximum temperature (C) decreases.

A strong positive relationship between latitude and maximum temperature can be observed in the Southern Hemisphere plot. The plot indicates as the latitide decreases the maximum temperature (C) increases.

For the Northern Hemisphere latitude vs humidity plot a weak positive relationship between latitude and humidity can be observed.

For the Southern Hemisphere latitude vs humidity plot a weak positive relationship between latitude and humidity can be observed.

For the Northern Hemisphere latitude vs cloudiness plot a positive relationship between latitude and humidity can be observed.

For the Southern Hemisphere latitude vs cloudiness plot a positive relationship between latitude and humidity can be observed.

For the Northern Hemisphere latitude vs wind speed plot a very weak positive relationship between latitude and wind speed can be observed. 

For the Southern Hemisphere latitude vs wind speed plot a negtaive relationship between latitude and wind speed can be observed.The closer the location of the city is to the Equator the more the wind speed decreases.


### VacationPy

VacationPy explores how to utilise Google Places API and gmaps to find your ideal holiday spot around the worl by setting your prefered weather conditions.

The 500+ list of cities was narrowed down based on the following criteria:

A max temperature lower than 35 degrees but higher than 20.
Wind speed less than 5 mph.
Zero cloudiness.

After filtering the ideal holiday spot a humidity heat map with hotel pin containng the hotel name, city and country was created.

