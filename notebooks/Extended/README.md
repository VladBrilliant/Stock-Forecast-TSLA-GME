# 📈 Extended Stock Forecast Project — TSLA & GME

<p align="center" style="margin:0 0 18px 0;">
  <img src="https://img.icons8.com/color/96/artificial-intelligence.png" width="85" alt="AI Brain"/>
  &nbsp;&nbsp;
  <code style="font-size:10px; color:#90a4ae;">
    import numpy as np, pandas as pd  
    from prophet import Prophet  
    from statsmodels.tsa.arima.model import ARIMA
  </code>
  &nbsp;&nbsp;<span style="font-size:26px;">🐍</span>
</p>

---

## 🔎 Overview

This is the **extended version** of the IBM Python Project for Data Science.  
While the [official project](../IBM_study/Python_Basics_for%20Data_Science_Project_1.ipynb) focused on data extraction and visualization, this extended notebook includes:

- 📊 Advanced forecasting (Prophet & ARIMA)  
- 🗂 Export pipelines (CSV, HTML, PNG, ZIP)  
- 📑 Tableau-ready long-format datasets  
- 🖼️ Visual dashboards (historical & forecasted trends)  

👉 IBM Cloud (unpolished due to *Lite plan limits*):  
[View Extended Project on IBM Cloud](https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/102cb6de-f796-4b64-813a-93be441410cf/view?access_token=b1c670e2a79a022625a032407740178eed2fab657d97f01877edf5f89862a456&context=cpdaas)  

👉 GitHub notebook (actively maintained):  
[Extended Project Notebook](Python_Project_for_Data_Science_Project_2.ipynb)

---

## 🏗️ Methods & Tools

**Data Extraction**
- `yfinance` — historical stock prices  
- `requests` + `BeautifulSoup` — revenue scraping from Macrotrends  

**Forecasting**
- `prophet` — trend detection & confidence intervals  
- `statsmodels` (ARIMA) — time series modeling  

**Visualization & Export**
- `plotly` — interactive dashboards  
- `kaleido` — static PNG export  
- `pandas` — data wrangling  
- `zipfile` — packaging results  

---

## 📊 Screenshots

<p align="center">
  <img src="https://github.com/VladBrilliant/Stock-Forecast-TSLA-GME/blob/main/notebooks/Extended/ibm_extended_screenshots/Screenshot_1.png" width="600"/><br>
  <i>Tesla: Monthly Close Forecast</i>
</p>

<p align="center">
  <img src="https://github.com/VladBrilliant/Stock-Forecast-TSLA-GME/blob/main/notebooks/Extended/ibm_extended_screenshots/Screenshot_2.png" width="600"/><br>
  <i>GameStop: Monthly Close Forecast</i>
</p>

<p align="center">
  <img src="https://github.com/VladBrilliant/Stock-Forecast-TSLA-GME/blob/main/notebooks/Extended/ibm_extended_screenshots/Screenshot_3.png" width="600"/><br>
  <i>Comparison: TSLA vs GME</i>
</p>

<p align="center">
  <img src="https://github.com/VladBrilliant/Stock-Forecast-TSLA-GME/blob/main/notebooks/Extended/ibm_extended_screenshots/Screenshot_4.png" width="600"/><br>
  <i>Forecast Confidence Intervals</i>
</p>

---

## 🚧 Work in Progress

This extended version is still being developed. Next steps include:
- 🔮 Adding more models (LSTM, XGBoost)  
- 📊 Benchmarking Prophet vs ARIMA vs ML models  
- 🌐 Publishing Tableau dashboard for broader exploration  

---

## 📌 Related

- [Official Project Notebook (IBM Study)](../IBM_study/Python_Basics_for%20Data_Science_Project_1.ipynb)  
- [Extended Project (GitHub)](Python_Project_for_Data_Science_Project_2.ipynb)  
- [IBM Cloud Version (incomplete, Lite plan limited)](https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/68ab5a8f-a206-44ce-b99a-3138c9c58935/view?access_token=5f105c703536a0133190b848a2d42cce055e9a2ebbd8bb04a7521d6c536ee475&context=cpdaas)  

---
