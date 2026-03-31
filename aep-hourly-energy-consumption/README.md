# ⚡ AEP Hourly Energy Consumption

## Description

The dataset contains hourly electricity consumption data for the **American Electric Power (AEP)** region in the United States.
It is part of a larger collection of power usage data from PJM Interconnection, a regional transmission organization.

Each row represents the total energy consumption at a specific hour, measured in megawatts (MW).
The dataset is commonly used for time series forecasting and energy demand analysis. 

## Target

* `AEP_MW` – hourly energy consumption (in megawatts)


## Features

* `Datetime` – timestamp of observation (hourly frequency)
* `AEP_MW` – electricity consumption

## Shape

* **Rows:** ~121,000
* **Columns:** 2

## Time Range

* Starts around: **2004**
* Covers multiple years of hourly data


## Notes

* Regular time intervals (**1 hour**)
* No additional features (pure time series)
* Data sourced from PJM (U.S. electricity grid operator) 
* Strong temporal patterns:

  * daily cycles (hour-of-day effects)
  * weekly patterns (weekday vs weekend)
  * seasonal trends (summer/winter peaks)

* Suitable for:

  * time series forecasting
  * load prediction
  * feature engineering (lags, rolling windows)
  * anomaly detection

## Example Use Cases

* Forecast hourly electricity demand
* Analyze peak consumption hours
* Build ML models (XGBoost, LSTM)
* Study seasonality and long-term trends

## Source

* PJM Interconnection (public energy data)
* Kaggle: *Hourly Energy Consumption* dataset https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption
