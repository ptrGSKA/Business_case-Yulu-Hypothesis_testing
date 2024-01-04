# Yulu Business Hypothesis Testing

Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.
Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

Yulu has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

## Objective

- Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
- How well those variables describe the electric cycle demands?

## Data description

    - datetime: datetime
    - season: 
            1: spring 
            2: summer
            3: fall 
            4: winter
    - holiday: whether day is a holiday or not
            1: yes
            0: no 
    - workingday: if day is neither weekend nor holiday is 1, otherwise is 0.
            1: weekday (not including holiday)
            0: weekend
    - weather: 
            1: Clear, Few clouds, partly cloudy   
            2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist   
            3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds    
            4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
    - temp: temperature in Celsius
    - atemp: real feel temperature in Celsius
    - humidity: humidity
    - windspeed: wind speed
    - casual: count of casual users
    - registered: count of registered users
    - count: count of total rental bikes including both casual and registered

# Description