# Paris weather prediction

## DATA

Weather data is downloaded from [Darksky](https://darksky.net/dev). The first 1000 accesses are totally free, but after that, the service will be shut down, unless one provides the payment method. 

I kept downloading data from the server for free regularly, so one can find the weather data in .csv format of about 4 years in the [data folder](https://github.com/SamWongML/weather_in_Paris/tree/master/data).

The .csv file contains columns as mentioned below:
* date
* time
* temperature
* apparent_temperature
* precip_intensity
* precip_probability
* dew_point
* humidity
* pressure
* wind_speed
* cloud_cover

## Weather prediction using machine learning

First approach:
* LSTM
* XGBoost
* Reinforced learning
