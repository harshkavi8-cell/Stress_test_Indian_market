# Portfolio Stress Testing – Indian Equity Portfolio

[![Open In Colab]https://colab.research.google.com/drive/1OTZiUAchHEC7SgWqHa7tNMl9hO4V1ha_?usp=sharing](https://github.com/yourusername/your-repo-name/blob/main/Portfolio_Stress_Test.ipynb)
---

## **Overview**
This project simulates **historical and hypothetical stress scenarios** on an Indian equity portfolio using real stock price data. It helps investors analyze potential **portfolio losses (PnL)** and **percentage changes** during major financial, geopolitical, and policy events, providing insight into risk exposure under extreme conditions.

---

## **Features**
- **Flexible portfolio input:** Supports multiple Indian stocks with custom weights and total portfolio value.
- **Historical stress scenarios:**
  - COVID-19 Crash (2020)
  - 2014 General Elections
  - Lehman Crisis (2008)
  - Trump Tariff Shock India (2025)
- **Automated portfolio valuation:** Computes daily portfolio value time series.
- **PnL and % change calculation:** Measures scenario impacts on portfolio performance.
- **Visualization:** 
  - Line charts for portfolio value over time
  - Bar charts for PnL percentage impact

---

## **Usage**
1. Open the notebook in Google Colab via the badge above.
2. Set your **portfolio tickers**, **weights**, and **total portfolio value**.
3. Run the notebook to compute **portfolio time series**, **stress-test results**, and **visualizations**.
4. Optionally, add or modify **historical or hypothetical scenarios**.

---

## **Dependencies**
- Python 3.x
- `pandas`
- `numpy`
- `yfinance`
- `matplotlib`
- Google Colab compatible

Install missing packages with:

```bash
pip install pandas numpy yfinance matplotlib
