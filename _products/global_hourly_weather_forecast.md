---
title: "Global Hourly Weather Forecast"
date: 2024-05-06T13:44:30+10:00
# image: "images/products/joseph-gonzalez-399972-unsplash.jpg"
# jobtitle: "Art Director"
# linkedinurl: ""
weight: 1
---

Global Hourly Weather Forecast API

Your passport to real-time weather insights, tailored for today's data-driven world. Designed to empower developers, businesses, and weather enthusiasts alike, our Global Hourly Weather Forecast API delivers comprehensive hourly forecasts worldwide in the next 5 days, covering every corner of the globe with precision and accuracy. Whether you're building a mobile app, powering a website, or integrating weather functionality into your business operations, our Global Hourly Weather Forecast API provides the tools you need to keep users informed and engaged.

Please see current available weather variables below and let us know if you need other variables. You can find detailed instructions from [Swagger UI](https://app.swaggerhub.com/apis-docs/measurespace.io/global-hourly_forecast_weather_api/0.1.0#/). This API data is also available on [AWS Data Exchange](https://aws.amazon.com/marketplace/pp/prodview-heghe5zjmqy26?sr=0-2&ref_=beagle&applicationId=AWSMPContessa#offers).

| name        | description                                                                      | standard unit | imperial unit | metric unit |
| ----------- | -------------------------------------------------------------------------------- | ------------- | ------------- | ----------- |
| weatherCode | weather code used for weather icons                                              | -             | -             | -           |
| timezone    | time zone name                                                                   | -             | -             | -           |
| tp          | total precipitation                                                              | mm            | inch          | mm          |
| t2m         | 2m air temperature                                                               | K             | F             | C           |
| u10         | 10m eastward wind                                                                | m/s           | miles/h       | km/h        |
| v10         | 10m northward wind                                                               | m/s           | miles/h       | km/h        |
| windSpeed   | 10m wind speed                                                                   | m/s           | miles/h       | km/h        |
| windDegree  | 10m wind direction (0-north, 180-south, clockwise)                               | degree        | degree        | degree      |
| r2          | relative humidity                                                                | %             | %             | %           |
| d2m         | dew point temperature                                                            | K             | F             | C           |
| sde         | snow depth                                                                       | m             | inch          | m           |
| sunsd       | sunshine duration                                                                | s             | s             | s           |
| dswrf       | downward shortwave radiation flux                                                | w/m^2         | w/m^2         | w/m^2       |
| vis         | visibility                                                                       | m             | miles         | km          |
| sp          | pressure                                                                         | Pa            | Pa            | Pa          |
| st          | top soil temperature                                                             | K             | F             | C           |
| crain       | rain (1) or not (0)                                                              | 0/1           | 0/1           | 0/1         |
| csnow       | snow (1) or not (0)                                                              | 0/1           | 0/1           | 0/1         |
| cicep       | ice pellets (1) or not (0)                                                       | 0/1           | 0/1           | 0/1         |
| cfrzr       | freezing rain (1) or not (0)                                                     | 0/1           | 0/1           | 0/1         |
| tcc         | total cloud cover                                                                | %             | %             | %           |
| prate       | precipitation rate                                                               | kg/m^2/s      | kg/m^2/s      | kg/m^2/s    |
| cape        | surface convective available potential energy                                    | J/kg          | J/kg          | J/kg        |
| precipType  | precipitation type (0-no precip, 1-rain, 2-snow, 3-freezing rain, 4-ice pellets) | 0/1/2/3/4     | 0/1/2/3/4     | 0/1/2/3/4   |
| apparentT   | apparent temperature (i.e. feels-like temperature)                               | K             | F             | C           |

