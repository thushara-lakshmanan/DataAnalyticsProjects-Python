
##### About the data

This dataset contains weather information from many of the weather stations around Australia. For most weather stations, we have about 365 observations for the years 2007 to 2017. More information about the dataset can be found in the Australian Bureau of Meteorology website, and below you can find a short description of the variables in the dataset.

Variables info:

 1. Date --> day, month, and year of the observation, each weather station has its own.
 2. Location --> location of the weather station.
 3. MinTemp --> minimum temperature for that day.
 4. MaxTemp --> maximum temperature for that day.
 5. Rainfall --> the amount of rainfall recorded for the day in mm.
 6. Evaporation --> the so-called Class A pan evaporation (mm) in the 24 hours to 9am
 7. Sunshine --> the number of hours of bright sunshine in the day
 8. WindGustDir --> the direction of the strongest wind gust in the 24 hours to midnight
 9. WindGustSpeed --> the speed (km/h) of the strongest wind gust in the 24 hours to midnight
 10. WindDir9am --> direction of the wind at 9am
 11. WindDir3pm --> direction of the wind at 3pm
 12. WindSpeed9am --> wind speed (km/hr) averaged over 10 minutes prior to 9am
 13. WindSpeed3pm --> wind speed (km/hr) averaged over 10 minutes prior to 3pm
 14. Humidity9am --> humidity (percent) at 9am
 15. Humidity3pm --> humidity (percent) at 3pm
 16. Pressure9am --> atmospheric pressure (hpa) reduced to mean sea level at 9am
 17. Pressure3pm --> atmospheric pressure (hpa) reduced to mean sea level at 3pm
 18. Cloud9am --> fraction of sky obscured by cloud at 9am. 
 19. Cloud3pm --> fraction of sky obscured by cloud at 3pm. 
 20. Temp9am --> temperature (degrees C) at 9am.
 21. Temp3pm --> temperature (degrees C) at 3pm.
 22. RainToday --> boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0
 23. RISK_MM --> the amount of next day rain in mm. Used to create response variable RainTomorrow. 
 24. RainTomorrow --> did it rain the following day?
