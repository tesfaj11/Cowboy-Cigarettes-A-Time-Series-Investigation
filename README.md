# Cowboy-Cigarettes-A-Time-Series-Investigation

**Project Duration:** 4–6 hours  
**Springboard Unit:** A Deep Dive into Time Series Analysis  
**Techniques Used:** ARIMA, SARIMA, ADF Test, Forecasting

---

## Project Overview

This project investigates historical cigarette sales for Cowboy Cigarettes, the longest-running U.S. cigarette manufacturer. The task was to analyze monthly sales data from 1949 to 1960 and forecast what likely happened in the early 1960s, before the next available data in 1970.

The insights generated from this analysis contribute to a broader public health report about tobacco consumption trends during that era.

---

## Objective

- Use time series modeling to predict if sales increased, decreased, or stayed the same between 1961 and 1965.
- Apply both ARIMA and SARIMA models for robust forecasting.
- Support public health insight with historical trend reconstruction.

---

## Tools and Techniques

| Tool/Library      | Purpose                          |
|------------------|----------------------------------|
| Python, Pandas   | Data cleaning and time parsing   |
| Matplotlib       | Visualizations                   |
| Statsmodels      | ARIMA/SARIMA modeling            |
| ADF Test         | Stationarity check               |

---

## Models Applied

### ARIMA(1,1,1)  
Captured the trend well and forecasted steady growth into the 1960s.

### SARIMA(1,1,0)(1,1,0,12)  
Handled seasonal patterns and revealed the same upward trend with monthly fluctuations.

---

## Final Conclusion

Both models suggest that Cowboy Cigarettes sales likely increased in the early 1960s.  
The forecast supports the idea that cigarette consumption remained high during this time, strengthening the case for future tobacco regulation.

---

## Files Included

- `Cowboy_Cigarettes_Tier3_ARIMA_SARIMA.ipynb` – Full notebook with ARIMA and SARIMA forecasts
- `CowboyCigsData.csv` – Original dataset (1949–1960)
