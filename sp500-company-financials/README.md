# 📈 S&P 500 Company Financials

## Description

The dataset contains financial and market data for companies listed in the S&P 500 index.
It includes valuation metrics, profitability indicators, and sector classifications.

Each row represents a single company.
The dataset is suitable for financial analysis, stock screening, and sector comparison.


## Target

* No explicit target
* Commonly created:

  * `is_undervalued` (e.g., low P/E)
  * `high_dividend`
  * `growth_vs_value`

## Features

### Company Info

* `Symbol` – stock ticker
* `Name` – company name
* `Sector` – industry sector

### Market Data

* `Price` – current stock price
* `Market Cap` – total market capitalization

### Valuation

* `Price/Earnings` – P/E ratio
* `Price/Sales` – P/S ratio
* `Price/Book` – P/B ratio

### Profitability

* `Earnings/Share` – earnings per share (EPS)
* `EBITDA` – earnings before interest, taxes, depreciation, and amortization

### Dividends

* `Dividend Yield` – dividend yield

### Price Range

* `52 Week Low` – lowest price in last 52 weeks
* `52 Week High` – highest price in last 52 weeks

### Other

* `SEC Filings` – link to official filings


## Shape

* **Rows:** 503
* **Columns:** 14


## Notes

* Mix of **numerical and categorical features**
* Some missing values (especially in financial ratios)
* Ratios may include **outliers** (very high or low values)
* Financial data reflects a specific snapshot in time

* Suitable for:

  * financial ratio analysis
  * stock screening
  * sector comparison
  * visualization of valuation metrics



## Example Use Cases

* Compare P/E ratios across sectors
* Identify undervalued companies (low P/E, reasonable price)
* Analyze dividend-paying stocks
* Study relationship between valuation and profitability


## Source
 
* GitHub: *datasets/s-and-p-500-companies-financials* https://github.com/datasets/s-and-p-500-companies-financials/tree/main
* Based on publicly available financial data

