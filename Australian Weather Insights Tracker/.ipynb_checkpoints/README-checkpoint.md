### Australian Weather Insights Tracker

##### About the data

This dataset contains weather information from many of the weather stations around Australia. For most weather stations, we have about 365 observations for the years 2007 to 2017. More information about the dataset can be found in the Australian Bureau of Meteorology website, and below you can find a short description of the variables in the dataset.

Variables info:

- Date --> day, month, and year of the observation, each weather station has its own.
- Location --> location of the weather station.
- MinTemp --> minimum temperature for that day.
- MaxTemp --> maximum temperature for that day.
- Rainfall --> the amount of rainfall recorded for the day in mm.
- Evaporation --> the so-called Class A pan evaporation (mm) in the 24 hours to 9am
- Sunshine --> the number of hours of bright sunshine in the day
- WindGustDir --> the direction of the strongest wind gust in the 24 hours to midnight
- WindGustSpeed --> the speed (km/h) of the strongest wind gust in the 24 hours to midnight
- WindDir9am --> direction of the wind at 9am
- WindDir3pm --> direction of the wind at 3pm
- WindSpeed9am --> wind speed (km/hr) averaged over 10 minutes prior to 9am
- WindSpeed3pm --> wind speed (km/hr) averaged over 10 minutes prior to 3pm
- Humidity9am --> humidity (percent) at 9am
- Humidity3pm --> humidity (percent) at 3pm
- Pressure9am --> atmospheric pressure (hpa) reduced to mean sea level at 9am
- Pressure3pm --> atmospheric pressure (hpa) reduced to mean sea level at 3pm
- Cloud9am --> fraction of sky obscured by cloud at 9am. 
- Cloud3pm --> fraction of sky obscured by cloud at 3pm. 
- Temp9am --> temperature (degrees C) at 9am.
- Temp3pm --> temperature (degrees C) at 3pm.
- RainToday --> boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0
- RISK_MM --> the amount of next day rain in mm. Used to create response variable RainTomorrow. 
- RainTomorrow --> did it rain the following day?

All these data are stored in one single csv file.The original data [weatherAUS.csv](https://raw.githubusercontent.com/thushara-lakshmanan/DataAnalyticsProjects-Python/master/Data/weatherAUS.csv)- is saved  in [data](https://github.com/thushara-lakshmanan/DataAnalyticsProjects-Python/tree/master/Data) folder.There is also a cleaned version called [weather_ready.csv](https://github.com/thushara-lakshmanan/DataAnalyticsProjects-Python/blob/master/Data/weather_ready.csv) in the same folder.

[**The Jupyter notebook for this analysis is saved as Australian_Weather_Insights_Tracker.ipynb**](hhttps://github.com/thushara-lakshmanan/DataAnalyticsProjects-Python/blob/master/Australian%20Weather%20Insights%20Tracker/Australian_Weather_Insights_Tracker.ipynb)

Table of contents

1. Load Data
2. Inspect Data
3. Clean & Prepare Data
4. Exploratory Data Analysis    
5. Summary
