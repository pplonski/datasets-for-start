# 📦 Datasets for Start

A curated collection of **simple, ready-to-use datasets** for machine learning, data analysis, and tutorials.

These datasets are designed to:

* ✅ be easy to load
* ✅ require minimal preprocessing
* ✅ work great for beginners and demos

## 🚀 Why this repo?

This repository helps you:

* learn machine learning faster
* practice exploratory data analysis (EDA)
* build quick prototypes
* create tutorials and demos

👉 No heavy data cleaning — just start working with data.


## 🧠 Use with MLJAR Studio

These datasets work perfectly with **MLJAR Studio** — a desktop app for data science.

With MLJAR Studio you can:

* load datasets instantly
* explore data visually
* run Python + no-code workflows
* build machine learning models
* generate plots and reports

👉 [https://mljar.com/](https://mljar.com)


## 📊 Dataset Overview

### 🔵 Binary Classification

| Dataset                 | Type      | Rows  | Target      |
| ----------------------- | --------- | ----- | ----------- |
| adult                   | tabular   | 48k   | income      |
| bank-marketing          | tabular   | 45k   | subscribed  |
| breast_cancer_wisconsin | tabular   | 569   | diagnosis   |
| credit                  | tabular   | 1k    | credit risk |
| diabetes                | tabular   | 768   | outcome     |
| employee_attrition      | tabular   | 1.5k  | attrition   |
| ionosphere              | tabular   | 351   | class       |
| sonar                   | tabular   | 208   | object      |
| spam                    | tabular   | 4.6k  | spam        |
| spect                   | tabular   | 267   | diagnosis   |
| 2d_circles              | synthetic | small | class       |
| 2d_simple               | synthetic | small | class       |
| 3d_spheres              | synthetic | small | class       |

### 🟣 Multiclass Classification

| Dataset | Type    | Rows | Target  |
| ------- | ------- | ---- | ------- |
| digits  | tabular | 1.8k | digit   |
| iris    | tabular | 150  | species |
| wine    | tabular | 178  | class   |
| glass   | tabular | 214  | type    |
| mnist   | image   | 70k  | digit   |


### 🟢 Regression

| Dataset                   | Type        | Rows  | Target     |
| ------------------------- | ----------- | ----- | ---------- |
| housing                   | tabular     | 506   | price      |
| house_prices              | tabular     | 1.4k  | sale price |
| housing_california        | tabular     | 20k   | price      |
| regression_1              | synthetic   | small | value      |
| regression_2              | synthetic   | small | value      |
| us_house_prices_1950_2024 | time series | ~900  | price      |


### 🟡 Time Series

| Dataset                       | Frequency | Rows  | Target     |
| ----------------------------- | --------- | ----- | ---------- |
| air-passengers                | monthly   | 144   | passengers |
| aep-hourly-energy-consumption | hourly    | ~121k | MW         |
| nyc-taxi-demand               | 30 min    | 10k   | demand     |
| bitcoin-historical-data       | 4H        | ~17k  | price      |


### 🟠 Business / Tabular

| Dataset                  | Rows  | Use Case            |
| ------------------------ | ----- | ------------------- |
| online-retail            | ~500k | e-commerce analysis |
| superstore-sales         | 51k   | business analytics  |
| telco-customer-churn     | 7k    | churn prediction    |
| sp500-company-financials | 500   | financial analysis  |


### 🟤 NLP

| Dataset                  | Rows | Task               |
| ------------------------ | ---- | ------------------ |
| amazon-fine-food-reviews | 10k  | sentiment / NLP    |
| imdb                     | 50k  | sentiment analysis |


### 🌍 Other

| Dataset                | Rows      | Task           |
| ---------------------- | --------- | -------------- |
| higgs                  | 11M       | classification |
| occupancy              | 20k       | classification |
| world_happiness_report | ~150/year | regression     |


## ⚡ Quick Start

```python
import pandas as pd

url = "https://raw.githubusercontent.com/pplonski/datasets-for-start/master/adult/data.csv"
df = pd.read_csv(url)

print(df.head())
```

## 📊 What can you build?

With these datasets you can practice:

* classification models
* regression models
* time series forecasting
* NLP (text analysis)
* business analytics


## 🤝 Contributing

If you have a dataset that is:

* simple
* clean
* useful for learning

Feel free to open a pull request 🚀


## 📄 License

MIT License

Datasets come from public sources (UCI, Kaggle, etc.).
Please check individual datasets for details.
