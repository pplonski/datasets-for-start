# 🛒 Online Retail

## Description

The dataset contains transactional data from a UK-based online retail store.
It includes all purchases made between December 2010 and December 2011.

Each row represents a single transaction line (a product within an invoice).
The dataset can be used to analyze sales trends, customer behavior, and product performance.

## Target

* No explicit target variable
* Commonly created targets:

  * `Revenue` (Quantity × UnitPrice)
  * `Churn` (customer-level)
  * `Repeat purchase` indicator

## Features

* `InvoiceNo` – invoice number (transaction ID)
* `StockCode` – product code
* `Description` – product name
* `Quantity` – number of items purchased
* `InvoiceDate` – date and time of transaction
* `UnitPrice` – price per item
* `CustomerID` – unique customer identifier
* `Country` – customer country


## Shape

* **Rows:** 541,909
* **Columns:** 8

## Notes

* Contains **missing values** (mainly in `CustomerID`)
* Includes **cancellations/returns** (negative `Quantity` or InvoiceNo starting with "C")
* Requires basic cleaning:

  * remove cancellations (optional)
  * handle missing customers
  * create `Revenue = Quantity * UnitPrice`
* Suitable for:

  * exploratory data analysis (EDA)
  * time series analysis (monthly revenue)
  * customer segmentation (RFM)
  * market basket analysis


## Source

* UCI Machine Learning Repository
* Kaggle https://www.kaggle.com/datasets/jihyeseo/online-retail-data-set-from-uci-ml-repo
