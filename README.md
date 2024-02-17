# Beijing Housing Price Forecast Project

## Overview
This project conducts an in-depth analysis of the housing market in Beijing from 2011 to 2017. It explores the influence of community and temporal changes on property values.

## Files in the Repository
- `housing_price_data_lianjia_2011_2017.csv` - Dataset for housing prices in Beijing.
- `main.ipynb` - Jupyter notebook with data analysis and model development.
- `report.pdf` - Comprehensive project report with findings and methodology.

## Model Details
An XGBoost regression model with Recursive Feature Elimination (RFE) identifies the top eight features impacting the "price per square" metric. The model is trained on data up to December 31, 2015, and tested on data from January 2016 onwards, demonstrating high accuracy and an upward trend in prices over time.

## Key Insights
- The model shows high accuracy with predictions that align closely with the actual data, especially in more recent years.
- `tradeYear` and `communityAverage` emerge as the most significant features, indicating the importance of temporal trends and local community valuations.

## Conclusions
The results underscore the real estate adage "location, location, location" and the value of time, reinforcing the need to consider both locational and temporal factors in property valuation.


