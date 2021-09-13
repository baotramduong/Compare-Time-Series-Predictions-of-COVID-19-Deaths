# Compare-Time-Series-Predictions-of-COVID-19-Deaths

## Blog

[Medium Blog](https://baotramduong.medium.com/compare-time-series-predictions-of-covid-19-deaths-using-sarimax-facebook-prophet-neural-network-c6f6f26b2582)

## Problem Statement

To contribute to the discussion of which model can be used for COVID-19 forecast, in this project, we will employ both Time Series Models, such as SARIMAX and Facebook Prophet, and non-Time Series Models i.e. machine learning models such as XGBoost and Neural Network. We will do a comparative analysis across these models and predict COVID-19 daily deaths.

## Data Source

We will use the COVID-19 Global Daily Deaths dataset by Johns Hopkins University for this project. 
This dataset is ranged from January 22, 2020 to August 16, 2020. The dataset is available in the time series format with date, month and year.

## Data Visualization

<img src = '../main/Data & Images/Cumulative Daily Death.png' />

<img src = '../main/Data & Images/Daily Death.png' />

## Modeling

### SARIMAX

<img src = '../main/Data & Images/sarimax_prediction.png' />

### Facebook Prophet

<img src = '../main/Data & Images/Prophet Prediction.png' />

## SARIMAX, Prophet, XGBoost, and Neural Network Comparison

<img src = '../main/Data & Images/Comparison.png' width='75%' height='75%' />

## Summary of Key Findings

|      |Model         |MAE   |
|------|--------------|------|
|0     |XG-Boost      |392.15|
|1     |Prophet       |572.56|
|2     |SARIMAX       |650.62|
|3     |Neural Network|728.0 |

## Future Work

* Build CNN or RNN models

* Build multivariate regression model with features such as vaccine coverage, hospital resource, mask use, social distancing etc.

* Include geographical, demographic and other facts.

## Reference

Abbas, S. A. (n.d.) Compare time series predictions of COVID-19 deaths [MOOC]. Coursera. https://www.coursera.org/projects/compare-time-series-predictions-of-covid19-deaths.

Brownlee, J. (2020, September 9). Time series forecasting performance measures with python. Machine Learning Mastery. Retrieved September 13, 2021, from https://machinelearningmastery.com/time-series-forecasting-performance-measures-with-python/#:~:text=The%20mean%20absolute%20error%2C%20or,is%20called%20making%20them%20absolute. 

Haltiwanger, J. (2021, January 20). More Americans have now died FROM COVID-19 than the number of US troops killed during World War II. Insider. Retrieved September 13, 2021, from https://www.businessinsider.com/more-americans-dead-covid-19-us-battle-deaths-wwii-2020-12. 

Ioannidis, J., Cripps, S., & Tanner, M. A. (2020). Forecasting for COVID-19 has failed. International journal of forecasting, 10.1016/j.ijforecast.2020.08.004. Advance online publication. https://doi.org/10.1016/j.ijforecast.2020.08.004.
