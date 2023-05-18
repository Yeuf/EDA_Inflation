# EDA_Inflation
Economic data analysis on the relation between inflation and major central bank interest rates in the UE and the US

This script uses the FRED API to retrieve and analyze data on US and EU inflation rates.

## Requirements

- pandas
- numpy
- matplotlib
- plotly
- fredapi

You will also need to obtain an API key from FRED and store it in a `config.py` file.

## Description

The script retrieves data on US inflation rates, the US federal fund rate, and EU inflation rates by country. It then generates several visualizations of the data using matplotlib and plotly.

The visualizations include:
- A line plot of US inflation rates over time
- A line plot of the US federal fund rate over time
- A line plot comparing US inflation rates and the federal fund rate
- A bar chart showing inflation rates by EU country for 2022
- Line plots of EU inflation rates and the ECB deposit rate over time
- A subplot grid showing inflation rates and the ECB deposit rate for each EU country over time.
