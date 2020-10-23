# PyBer_Analysis

## Overview of Project
---
The purpose of this project is to create an easy-to-read summary dataframe of the PyBer data, while also using 2 new functions - pivot() and resample() - to analyze datetime data and plot trends based on it.  


### Purpose of Analysis
For the first part of the analysis, we will create a new DataFrame that easily illustrates the Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver for each City Type (Rural, Suburban, Urban).  These high-level figures will help PyBer focus resources on further analysis, or company initiatives.  

In the second part, we will perform a deeper-dive into the information, so we can see performance by week in each City Type.  This information can be used to make budgets, identify anomalies (special events, etc.), or provide forecast information to stakeholders.  It will be presented in a line chart that clearly and boldly illustrates the trends.  

### Results 

### Differences in Data by City Type 

![Summary by City Type]("analysis/Summary_data_frame.png")
![Total Fare by City Type]("analysis/PyBer_fare_summary.png")

Comparing the city types in the DataFrame, we see that Urban cities have much higher driver counts, combined with lower average fares per ride and per driver.  Note that the average fare per ride is higher than the average fare per driver in Urban cities only.  Suburban and Rural cities each have a higher fare per driver than they do average fare per ride.  

Reviewing the Line Chart, there is a clear lift in all 3 City Types at the end of February 2019.  Urban cities have more fare peaks than Suburban and Rural.  Suburban fares sharply rise starting in the middle of April, and could possibly continue to trend after the upper limit of the chart (April 29, 2019).

### Summary Recommendations

1. Limit number of Urban City Drivers: There are more drivers than needed based on the current fare structure in Urban Cities.  The average driver is making less than the average ride fare, so unless we can expect a strong increase in rides or fares (while keeping driver count flat), this will not change.  

2. Create a marketing plan to attract more Rural Drivers: There is clearly demand for more drivers in Rural cities, due to the Average fare per driver being more than $20 higher than the average fare per ride.  If we increase Rural Drivers by 50% (to approx. 110) there will still be more than enough business to go around, while creating less reliance on a specific set of drivers to carry our business.  

3. Demand-based Pricing: We can use the Fares by Week data to determine trends (over a longer period of time) to see if demand-based pricing can help us capture revenue that we are potentially missing.  While other ride share companies base this on driver counts, we can clearly see that there are multiple opportunities for fare increases in Urban Cities.  If the peaks on the line chart are based on local events, holidays, or other things that can be predicted, we can make a lot more Fare Revenue by gently increasing prices during those times.  
