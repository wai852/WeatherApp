# WeatherApp

#### Introduction:
It retrieves data from Weather API(Openweathermap) by using Retrofit2.
1. Receive weather information
   1. search by the name of the city
   2. search by current location

#### Uses-permission:
1. android.permission.ACCESS_FINE_LOCATION
2. android.permission.ACCESS_COARSE_LOCATION
3. android.permission.INTERNET

#### API:
Weather API
Base Url is using the version 2.5 of Weather API: https://api.openweathermap.org/data/2.5/
   1. weather?lat={value}&lon={value}&appid={your_key}&units=metric
   2. weather?q={name_of_city}&appid={your_key}&units=metric

#### Database:
NONE

#### Create At:
10/01/2022
