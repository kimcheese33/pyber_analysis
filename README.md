# PyBer Analysis

## Overview

The purpose of this analysis was to use MapPlotLib and Pandas to analyze and create visualizations on PyBer data to see where improvements could be made. Using Pandas, we created dataframes to show how rides, fares, and number of drivers differed based on whether a city was urban, suburban, or rural. We used MapPlotLib to create a line chart showing the results.

## Results

Here are the differences between each city:

- Urban: Urban cities had the highest number of rides and drivers. While also having the lowest average fare per ride and per driver, urban cities still came out with the highest total fare.

- Suburban: Suburban cities had a little less than half the number of rides compared to urban cities. Suburban cities also had about 1/5 of the total number of drivers compared to urban cities. The average fare per ride was about $6 more than urban fares. In addition, suburban average fare per driver was more than double the average fare per driver for urban cities. Despite the higher average fares, suburban city fares were only about half of the total fares for urban cities.

- Rural: Rural cities came out with the lowest number of rides and drivers. Rural cities also had the highest average fare per ride and per driver. The total fares for rural cities was way less than suburban and urban total fares.

See below for the results by city:

<img src="https://github.com/kimcheese33/pyber_analysis/blob/main/analysis/pyber_summary.png"/>

<img src="https://github.com/kimcheese33/pyber_analysis/blob/main/analysis/PyBer_fare_summary.png"/>

## Summary

To address the disparities among types of cities, here are my recommendations:

1. Rural areas currently have the worst performance as far as number of rides go. This is likely due to the high average fares we are seeing and the fact that rural residents tend to cars. To address this, I recommend lowering the average fare per ride by about $5 and the average fare per driver by $5-10 by offering riders a temporary discount. Based on how offering a discount turns out, you could implement the lowered fare permanently.

2. The current situation in suburban cities is in fairly good shape, so I would recommend just lowering the price per ride and per driver by a dollar or two. This could boost more rides.

3. For urban cities we are seeing the highest number of rides. This might be due to the lower fares or might be due to urban residents' tendency to not own cars. If it's the latter, I would recommend raising fares by a dollar or two. The need to take public transportation or ride with Pyber might result in higher revenue despite raising the fare as people still need to get from point A to point B.
