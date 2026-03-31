# ₿ Bitcoin 4H Market Data (2018–2026)

## Description

The dataset contains historical Bitcoin (BTC) market data sampled at **4-hour intervals**.
Each row represents a single candlestick with price information (OHLC) and trading activity metrics.

The data spans multiple market cycles, including bull and bear periods, making it suitable for financial modeling and time series analysis.

## Target

* No explicit target variable
* Commonly derived targets:

  * `future_return`
  * `price_direction` (up/down)
  * `volatility`

## Features

* `open_time` – start of the 4-hour interval
* `open` – opening price
* `high` – highest price
* `low` – lowest price
* `close` – closing price
* `volume` – traded volume (base asset)
* `close_time` – end of the interval
* `quote_asset_volume` – traded volume in quote currency (e.g., USDT)
* `number_of_trades` – number of executed trades
* `taker_buy_base_volume` – buy volume (base asset)
* `taker_buy_quote_volume` – buy volume (quote asset)
* `ignore` – unused column

## Shape

* **Rows:** ~17,960
* **Columns:** 12

## Time Range

* **Start:** 2018-01-01
* **End:** 2026-03-15
* **Frequency:** 4 hours


## Notes

* Regular time intervals (**4H candles**)
* No missing timestamps (continuous series)
* Financial time series characteristics:

  * high volatility
  * non-stationarity
  * regime shifts (bull / bear markets)

* Feature engineering is essential:

  * returns (`pct_change`)
  * rolling statistics
  * technical indicators (RSI, MACD, moving averages)

* Suitable for:

  * time series forecasting
  * algorithmic trading
  * anomaly detection
  * feature engineering experiments

## Example Use Cases

* Predict short-term price movements
* Build trading strategies
* Analyze volatility across market cycles
* Backtest technical indicators

## Source

* Kaggle: *Bitcoin Historical Datasets 2018–2024* https://www.kaggle.com/datasets/novandraanugrah/bitcoin-historical-datasets-2018-2024?select=btc_4h_data_2018_to_2025.csv
* Extended with recent market data (up to 2026)
* Data originally collected from cryptocurrency exchange APIs (e.g., Binance)



