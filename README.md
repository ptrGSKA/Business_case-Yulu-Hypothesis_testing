# Yulu Business Hypothesis Testing

Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.
Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

Yulu has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

## Objective

- Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
- How well those variables describe the electric cycle demands?
- Which features play a crucial role in determining the demand?
- What are the short term predictions?

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

## Description

During the initial phase, the dataset undergoes a process of identifying missing data, determining the data type of the feature variables and identifying the target variable. Additionally, an initial feature engineering step is performed to encode certain features, which aids in providing a more descriptive and representative representation of the data.  

Once the initial steps have been completed, the data is then visualized and aggregated in diverse ways during the explanatory data analysis phase. This enables a deeper understanding of the factors driving the fluctuations in demand.  

The subsequent data is then collapsed from an hourly format to daily records, and the corresponding features are modified accordingly.  

The section dedicated to data visualization provides insights into the weather patterns within the dataset and the corresponding demand across various seasons.  

In the sections dedicated to statistical analysis and model building, the data is subjected to hypothesis testing, also determining the significance of features and undergoes time series analysis using ARIMA to construct a model capable of making short-term predictions for future demand.

## Libraries used

- pandas
- matplotlib
- seaborn
- SciPy
- scikit-learn
- statsmodels
- pmdarima

## File Structure

```
📦Business_case-Yulu-Hypothesis_testing
 ┣ 📜.gitignore
 ┣ 📜README.md
 ┣ 📜Yulu_Business_Hypothesis_Testing.ipynb
 ┗ 📜yulu_bike_sharing_dataset.csv
```