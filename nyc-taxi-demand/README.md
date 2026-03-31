# 🚖 NYC Taxi Demand (Subsampled)

## Description

The dataset contains time series data representing taxi demand in New York City.
It is a subsampled version of aggregated taxi passenger counts, with observations recorded at regular 30-minute intervals.

Each row represents the total number of taxi passengers at a given timestamp.
The dataset is suitable for time series analysis, forecasting, and anomaly detection.

## Target

* `value` – number of taxi passengers (demand) at a given timestamp


## Features

* `timestamp` – date and time of observation (30-minute intervals)
* `value` – aggregated passenger count

## Shape

* **Rows:** 10,320
* **Columns:** 2

## Time Range

* **Start:** 2014-07-01 00:00:00
* **End:** 2015-01-31 23:30:00

## Notes

* Regular time intervals (**30 minutes**)

* No additional features (pure time series)

* Subsampled from a larger dataset (Numenta Anomaly Benchmark)

* Likely contains:

  * daily patterns (rush hours)
  * weekly seasonality
  * potential anomalies (holidays, events)

* Suitable for:

  * time series forecasting
  * anomaly detection
  * seasonality analysis
  * trend decomposition
    
## Example Use Cases

* Plot taxi demand over time
* Detect peak hours and trends

## Source

* Numenta Anomaly Benchmark (NAB) https://raw.githubusercontent.com/numenta/NAB/master/data/realKnownCause/nyc_taxi.csv
* Subsampled for educational / analysis purposes https://www.kaggle.com/datasets/elemento/nyc-yellow-taxi-trip-data


* Forecast future demand
* Identify anomalies in traffic patterns
