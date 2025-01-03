---
title: "Global Daily Weather Forecast"
date: 2024-05-06T15:44:30+10:00
# image: "images/products/nonsap-visuals-kMJp7620W6U-unsplash.jpg"
# jobtitle: "Graphic Designer"
# linkedinurl: ""
weight: 2
---

Global Daily Weather Forecast API

Your gateway to comprehensive weather predictions on a global scale, tailored for seamless integration into your applications and services. Our Global Daily Weather Forecast API delivers reliable daily forecasts in the next 15 days for locations across the world, empowering you to make informed decisions based on accurate weather insights. Whether you're developing a travel app, optimizing agricultural operations, or planning outdoor events, our Global Daily Weather Forecast API provides the essential tools to keep users informed and prepared for whatever the weather may bring.

Please see current available weather variables below and let us know if you need other variables. You can find detailed instructions from [Swagger UI](https://app.swaggerhub.com/apis-docs/measurespace.io/global-daily_forecast_weather_api/0.1.0). This API data is also available on [AWS Data Exchange](https://aws.amazon.com/marketplace/pp/prodview-ixlsy4vwvkj3u?sr=0-1&ref_=beagle&applicationId=AWSMPContessa).

| name           | description                                                                      | standard unit | imperial unit | metric unit |
| -------------- | -------------------------------------------------------------------------------- | ------------- | ------------- | ----------- |
| weatherCode    | weather code used for weather icons                                              | -             | -             | -           |
| timezone       | time zone name                                                                   | -             | -             | -           |
| sunrise        | sunrise time                                                                     | -             | -             | -           |
| sunset         | sunset time                                                                      | -             | -             | -           |
| tp             | daily total precipitation                                                        | mm            | inch          | mm          |
| minT           | daily minimum temperature                                                        | K             | F             | C           |
| maxT           | daily maximum temperature                                                        | K             | F             | C           |
| meanT          | daily mean temperature                                                           | K             | F             | C           |
| meanUWind      | daily mean eastward wind                                                         | m/s           | miles/h       | km/h        |
| meanVWind      | daily mean northward wind                                                        | m/s           | miles/h       | km/h        |
| meanwindSpeed  | daily mean wind speed                                                            | m/s           | miles/h       | km/h        |
| meanwindDegree | daily mean wind direction (0-north, 180-south, clockwise)                        | degree        | degree        | degree      |
| meanRH         | daily mean relative humidity                                                     | %             | %             | %           |
| meanDP         | daily mean dew point temperature                                                 | K             | F             | C           |
| snow           | daily accumulated snow depth                                                     | m             | inch          | m           |
| sunshine       | daily accumulated sunshine duration                                              | s             | s             | s           |
| solarR         | daily accumulated downward shortwave radiation flux                              | w/m^2         | w/m^2         | w/m^2       |
| meanVis        | daily mean visibility                                                            | m             | miles         | km          |
| pressure       | daily mean pressure                                                              | Pa            | Pa            | Pa          |
| meanST         | daily mean top soil temperature                                                  | K             | F             | C           |
| maxST          | daily maximum top soil temperature                                               | K             | F             | C           |
| minST          | daily minimum top soil temperature                                               | K             | F             | C           |
| meanSoilw      | daily mean top soil moisture                                                     | -             | -             | -           |
| crain          | rain (1) or not (0)                                                              | 0/1           | 0/1           | 0/1         |
| csnow          | snow (1) or not (0)                                                              | 0/1           | 0/1           | 0/1         |
| cicep          | ice pellets (1) or not (0)                                                       | 0/1           | 0/1           | 0/1         |
| cfrzr          | freezing rain (1) or not (0)                                                     | 0/1           | 0/1           | 0/1         |
| cfrzr          | freezing rain (1) or not (0)                                                     | 0/1           | 0/1           | 0/1         |
| meanTcc        | daily mean total cloud cover                                                     | %             | %             | %           |
| maxPrate       | daily max precipitation rate                                                     | kg/m^2/s      | kg/m^2/s      | kg/m^2/s    |
| maxCape        | daily max surface convective available potential energy                          | J/kg          | J/kg          | J/kg        |
| precipType     | precipitation type (0-no precip, 1-rain, 2-snow, 3-freezing rain, 4-ice pellets) | 0/1/2/3/4     | 0/1/2/3/4     | 0/1/2/3/4   |
| minApparentT   | minimum apparent temperature (i.e. feels-like temperature)                       | K             | F             | C           |
| maxApparentT   | maximum apparent temperature (i.e. feels-like temperature)                       | K             | F             | C           |


Note: For daily variables, you can get daytime and nighttime variables for local time by adding `daytime_` or `nighttime_` before the variable names.
For example, if you want to get daytime or nighttime total precipitation, you can use variable names `daytime_tp` or `nighttime_tp`.

