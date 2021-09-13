# Compare-Time-Series-Predictions-of-COVID-19-Deaths

## Blog

[Medium Blog]()

## Problem Statement

To contribute to the discussion of which model can be used for COVID-19 forecast, in this project, we will employ both Time Series Models, such as SARIMAX and Facebook Prophet, and non-Time Series Models i.e. machine learning models such as XGBoost and Neural Network. We will do a comparative analysis across these models and predict COVID-19 daily deaths.

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

Haltiwanger, J. (2021, January 20). More Americans have now died FROM COVID-19 than the number of US troops killed during World War II. Insider. Retrieved September 13, 2021, from https://www.businessinsider.com/more-americans-dead-covid-19-us-battle-deaths-wwii-2020-12. 

Ioannidis, J., Cripps, S., & Tanner, M. A. (2020). Forecasting for COVID-19 has failed. International journal of forecasting, 10.1016/j.ijforecast.2020.08.004. Advance online publication. https://doi.org/10.1016/j.ijforecast.2020.08.004
