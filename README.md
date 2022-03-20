# PyBer Analysis

## Overview

### Purpose

As part of our work at PyBer, a Python-based ride-share service, we have been tasked with creating a summary DataFrame of the ride-sharing data by city type using provided large datasets (CSV files). We need to create a multiple-line graph that shows the total weekly fares for each city type and a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

### Resources
- city_data.csv
- ride_data.csv

### Technologies
- Python
- Pandas
- Matplotlib

## Results

### City Type Analysis

![summary_df.JPG](https://github.com/mathur-nikita/PyBer_Analysis/blob/main/screenshots/summary_df.JPG)

As can been seen by the chart above:

- Urban cities have the most rides, followed by suburban and then rural cities.
- Urban cities have the most drivers, followed by suburban and then rural cities.
- Urban cities have the highest total of fares, followed by suburban and then rural cities.
- Rural cities have the highest average fare per ride, followed by suburban and then urban cities.
- Rural cities have the highest average fare per driver, followed by suburban and then urban cities.

### Time Based Analysis

![total_fare_chart.JPG](https://github.com/mathur-nikita/PyBer_Analysis/blob/main/screenshots/total_fare_chart.JPG)

As can be seen by the chart above:

- Fares in urban cities showed an overall increase over time, but this is not a stable increase as there are multiple times in which the fares changed per month (ex. end of February through March).
- Fares in suburban cities and urban cities tend to be more stable with fewer points of volatility compared to urban cities, with rural cities being the most stable.

## Summary

Some recommendations based on the above analysis:
1) Despite average fares being the higest in rural cities, they make up less than 7% of the combined fares across all city types.  It would be worth looking into options to increase the performance of PyBer in rural cities, maybe by setting a cap on fares to draw more customers in or offering special rates for specific situations.
2) In suburban and rural cities the number of drivers is lower than the total number of rides.  PyBer might benefit from recruiting more drivers in these cities to accomodate demand and contribute to a decrease in average fares per customer without the company losing money.
3) Some research should be done on the volatility of pricing in urban cities to determine the causes (ex. events and holidays) and then put some plans in place to help decrease that instability.
