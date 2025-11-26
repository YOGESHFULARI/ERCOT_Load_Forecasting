# ERCOT Load Forecasting Project

This project predicts **ERCOT electricity load** for the next 30 days using **SARIMA** and **Prophet** models in Python.  

## Dataset
- `ercot_load.xlsx`: Historical ERCOT load (MW)
- `ercot_30day_forecast.xlsx`: Forecasted load for next 30 days (hourly)

## Features
- Time series decomposition
- Stationarity check
- SARIMA modeling
- Forecast visualization
- Export forecasts to Excel

## How to Run
1. Open `ERCOT_Load_Forecasting.ipynb` in Jupyter Notebook or Google Colab.
2. Run all cells step by step.
3. Check forecast results in `ercot_30day_forecast.xlsx`.

## Libraries Required
- pandas, numpy, matplotlib, seaborn
- statsmodels, prophet
