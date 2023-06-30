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

This project involves retrieving data on US inflation rates, the US federal fund rate, and EU inflation rates by country. The script utilizes matplotlib and plotly libraries to generate various visualizations based on the acquired data.

The visualizations include:
- A line plot showcasing the trend of US inflation rates over time.
- A line plot illustrating the changes in the US federal fund rate over time.
- A line plot comparing US inflation rates and the federal fund rate, highlighting any potential correlations.
- A bar chart presenting the inflation rates by country for the year 2022 within the European Union (EU).
- Line plots demonstrating the variation of EU inflation rates alongside the European Central Bank (ECB) deposit rate over time.
- A subplot grid displaying the inflation rates and ECB deposit rate for each EU country, allowing for easy comparison over time.
