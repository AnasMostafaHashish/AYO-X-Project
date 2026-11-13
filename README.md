# AYO-X: Alexandria Precipitation Trend Analysis (2010–2025)
**NASA Space Apps Challenge**

## Overview
- **Participant:** Anas Mostafa (Team AYO-X)
- **Challenge:** Be An Earth System Trend Detective!
- **Objective:** Analyze monthly precipitation trends and identify extreme weather events in Alexandria, Egypt over a 15-year period (2010–2025) using satellite observations.

## Data Source
- **Platform:** NASA GPM IMERG Final Run (Monthly, 0.1°)
- **Tool:** NASA Giovanni Platform

## Methodology & Workflow
1. **Data Acquisition:** Downloaded monthly area-averaged precipitation and random error time-series datasets for Alexandria.
2. **Data Cleaning & Preprocessing:** Used Python (Pandas/NumPy) to handle metadata headers, merge datasets, and filter missing or invalid values.
3. **Trend Analysis:** Calculated 12-month rolling averages, linear trend regression, and identified extreme precipitation peaks exceeding 80 mm/month.

## Repository Contents
- `g4.areaAvgTimeSeries.GPM_3IMERGM_07_precipitation.20100101-20251231.29E_30N_30E_31N.csv`: Raw precipitation dataset.
- `g4.areaAvgTimeSeries.GPM_3IMERGM_07_randomError.20100101-20251231.29E_30N_30E_31N.csv`: Raw random error dataset.
- `Alexandria_Cleaned_Precipitation_2010_2025.csv`: Cleaned and processed dataset.
- `alexandria_precipitation_trend.png`: Basic monthly precipitation time-series chart.
- `alexandria_trend_analysis.png`: Advanced trend visualization chart (rolling average, linear trend, and extreme events).
- `AYO-X Pro - The data analysis - Colab.ipynb`: Jupyter Notebook containing the full analysis pipeline.
