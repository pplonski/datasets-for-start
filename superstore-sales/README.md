# 🏬 Superstore Sales (Global)

## Description

The dataset contains transactional sales data from a global retail superstore.
It includes detailed information about orders, customers, products, and shipping across multiple regions worldwide.

Each row represents a single product within an order.
The dataset is commonly used for business analytics, EDA, and dashboarding.

## Target

* No explicit target
* Commonly created:

  * `Sales`
  * `Profit`
  * `is_profitable`

## Features

### Order Information

* `Row ID` – unique row identifier
* `Order ID` – order identifier
* `Order Date` – date of order
* `Ship Date` – shipping date
* `Ship Mode` – shipping method
* `Order Priority` – priority level

### Customer Information

* `Customer ID` – unique customer ID
* `Customer Name` – customer name
* `Segment` – customer segment

### Location

* `City` – city
* `State` – state/region
* `Country` – country
* `Postal Code` – postal code (may be missing)
* `Market` – market (e.g., APAC, EMEA)
* `Region` – region

### Product Information

* `Product ID` – product identifier
* `Category` – product category
* `Sub-Category` – product sub-category
* `Product Name` – product name

### Sales & Metrics

* `Sales` – revenue
* `Quantity` – number of items
* `Discount` – discount applied
* `Profit` – profit (can be negative)
* `Shipping Cost` – shipping cost

## Shape

* **Rows:** 51,290
* **Columns:** 24


## Time Range

* Starts: **2011**
* Covers multiple years of sales data

## Notes

* Each order can contain multiple rows (one per product)
* Mix of **categorical and numerical features**
* Some missing values (e.g., `Postal Code`)
* Realistic global business dataset

* Suitable for:

  * exploratory data analysis (EDA)
  * business intelligence dashboards
  * sales and profit analysis
  * customer segmentation


## Example Use Cases

* Analyze profit by region and category
* Identify top customers and products
* Study discount impact on profitability
* Build BI dashboards (Tableau / Power BI)


## Source

* Kaggle: *Superstore Data* https://www.kaggle.com/datasets/jr2ngb/superstore-data 

