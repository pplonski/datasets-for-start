# ✈️ Air Passengers

## Description

The dataset contains monthly totals of international airline passengers from 1949 to 1960.
It is a classic time series dataset used for demonstrating forecasting methods and seasonal pattern analysis.

Each row represents the number of passengers for a given month.

## Target

* `Passengers` – total number of airline passengers per month


## Features

* `Month` – date (year-month format)
* `Passengers` – number of passengers

## Shape

* **Rows:** 144
* **Columns:** 2

## Notes

* Clean dataset (no missing values)
* Strong **trend and seasonality**:

  * increasing number of passengers over time
  * repeating yearly seasonal patterns
* Commonly used for:

  * time series forecasting
  * decomposition (trend + seasonality)
  * ARIMA / exponential smoothing models

## Example Use Cases

* Forecast future passenger numbers
* Detect seasonal patterns
* Compare time series models

## Source

* Box & Jenkins (1976)
* Kaggle https://www.kaggle.com/datasets/rakannimer/air-passengers
