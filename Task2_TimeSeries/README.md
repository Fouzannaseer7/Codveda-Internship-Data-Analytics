
# 📈 Task 2 – Time Series Analysis on Stock Prices

This notebook performs Time Series Analysis on stock price data as part of the Codveda Internship Program. The goal is to uncover trends, patterns, and seasonality in financial time series using Python.

---

## 📁 Dataset Details

- **Dataset Name:** `2) Stock Prices Data Set.csv`
- **Columns Present:** `symbol`, `open`, `high`, `low`, `close`, `volume`
- ❗ **Note:** The dataset did not contain a `Date` column. A synthetic date range was generated for the first 365 rows to simulate daily time series behavior.

---

## 🎯 Objectives

- Simulate a valid time series with synthetic dates
- Plot the stock’s closing price over time
- Decompose the time series into:
  - **Trend**
  - **Seasonality**
  - **Residuals**
- Apply moving average smoothing (7-day and 30-day)

---

## 📊 Key Insights

- The **7-day and 30-day moving averages** helped reduce short-term noise and visualize price trends clearly.
- **Seasonal decomposition** broke the closing price into components for better understanding of the structure behind the data.
- This technique can be extended to real-time stock data with valid timestamps for more advanced analysis and forecasting.

---

## 🧪 Tools Used

- Python  
- pandas  
- matplotlib  
- statsmodels  
- Jupyter Notebook

---

## 📄 File

- `Time_Series_Stock.ipynb`

---

## 🙋‍♂️ About Me

I'm **Fouzan Naseer**, a data analytics intern at Codveda. This project helped me explore time series fundamentals and their application in financial data analysis.

---

⭐ If you found this project useful, feel free to check out the other tasks in this repository!
