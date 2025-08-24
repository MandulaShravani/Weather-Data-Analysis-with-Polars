# Weather-Data-Analysis-with-Polars
This project focuses on Exploratory Data Analysis (EDA) of Toronto’s historical weather data using the Polars library in Python. The dataset includes hourly measurements of temperature, apparent temperature, precipitation, wind speed, sunshine duration, radiation, and more.
The aim is to analyze, clean, and derive insights from the dataset with efficient DataFrame operations using Polars.

**Tech Stack**
- Python 3.10+
- Polars (for fast dataframe operations)
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook / IDE

**Dataset**

The dataset was generated from the Open-Meteo API with parameters:
Location: Toronto, Canada (43.7001° N, -79.4163° W)
Timeframe: 2000-02-02 to 2025-05-03
Hourly features:
- temperature_2m
- apparent_temperature
- precipitation
- wind_speed_10m
- snow_depth
- sunshine_duration
- direct_radiation
- wind_gusts_10m

**Key Tasks Performed**

✔️ Data Loading & Cleaning

✔️ Handling Null Values

✔️ Ranking Radiation Levels

✔️ Pivot-style Aggregations (Hourly Averages)

✔️ Daily Summary Report (avg temp, total precipitation, total sunshine)

✔️ Feels-like Temperature Difference Analysis

✔️ Sorting & Filtering Insights

**Sample Insights**
- Days with highest solar radiation and their ranks.
- Difference between temperature vs. apparent temperature (feels-like).
- Daily weather summaries with average temperature and total sunshine hours.
