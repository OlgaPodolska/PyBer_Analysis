# PyBer_Analysis

## Overview of the analysis:

Purpose of this analysis was creating a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type. Then submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer. Using Python, Pandas and Matplotlib. 


## Results:

### The differences in ride-sharing data among the different city types

1. get the total number of rides, total number of drivers, and the total fares for each city type. Then, calculate the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, then format the columns

![formatted.png](/Resources/formatted.png) 

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type

### The differences in weekly bins


2. create a new DataFrame, 

![dates.png](/Resources/dates.png) 

Resample the data in weekly bins, then apply the sum() method to get the total fares for each week.

![result.png](/Resources/result.png) 

### Multiple-line graph

3. create a multiple-line graph that shows the total fares for each week by city type

![PyBer_fare_summary.png](/analysis/PyBer_fare_summary.png)



## Summary: 

Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

> * The Suburban fares started ~$1,000 -not profitable-fare dropped in March and in mid-April.  
> * The Rural fares started at ~$200-fares increase and dropped till the end of April.  
> * The Urban fares start with an average of $1,800 - consistent increase to ~$2,300. 
Summary

Opportunities to expand the business in rural and suburban cities, including hiring drivers
The Urban cities - opportunities to expand rides.
The Rural cities - opportunity to expand fares Total Fare by City Type