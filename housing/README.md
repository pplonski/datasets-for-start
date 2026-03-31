# 🏠 Boston Housing

## Description

The dataset contains information about housing in suburbs of Boston, Massachusetts.
It includes various socioeconomic and environmental features, with the goal of predicting house prices.

Each row represents a census tract, described by attributes such as crime rate, number of rooms, and accessibility to highways.
The dataset was collected by the U.S. Census Service and has been widely used as a benchmark for regression tasks. ([U of T Computer Science][1])

## Target

* `MEDV` – median value of owner-occupied homes (in $1000s)


## Features

* `CRIM` – per capita crime rate by town
* `ZN` – proportion of residential land zoned for large lots
* `INDUS` – proportion of non-retail business acres
* `CHAS` – Charles River dummy variable (1 if near river)
* `NOX` – nitric oxide concentration
* `RM` – average number of rooms per dwelling
* `AGE` – proportion of older houses (built before 1940)
* `DIS` – distance to employment centers
* `RAD` – accessibility to highways
* `TAX` – property tax rate
* `PTRATIO` – pupil-teacher ratio
* `B` – demographic-related feature
* `LSTAT` – percentage of lower-status population


## Shape

* **Rows:** 506
* **Columns:** 14 (13 features + 1 target)

## Notes

* No missing values
* Small dataset (good for quick experiments)
* Commonly used for:

  * regression
  * feature importance analysis
* ⚠️ Contains sensitive socioeconomic variables (use with care in modern applications)


## Source

* UCI Machine Learning Repository https://archive.ics.uci.edu/ml/datasets/Housing
* Harrison & Rubinfeld, 1978
