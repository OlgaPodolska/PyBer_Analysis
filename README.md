# PyBer_Analysis

## Overview of the analysis:

Purpose of this analysis was to find out the disparities between ride-sharing process in the different types of cities. For that purpose we created summary DataFrames of the ride-sharing data and a multiple-line graph that shows the total weekly fares for each city type. The current written report summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer. Using Python, Pandas and Matplotlib. 


## Results:

### The differences by city type

We got the total number of rides, total number of drivers, and the total fares for each city type from the provided data, and calculated the average fare per ride and average fare per driver for each city type. The result is presented in this DataFrame with formatted the columns: ![formatted.png](/Resources/formatted.png) 

We can clearly see that in the urban cities ride-sharing is more popular: they have the biggest total number of rides, drivers and naturally that leads to the biggest amount of total fares. But it happens because of numbers of cheap rides: average fares in the urban cities are smallest from all of them.

On the other side, the rural cities have most expencive average fares, but the total number of rides and drivers isn't very big, so total fires of rural cities are the smallest. Most probably it is due to the low population density in the rural cities, but this hypothesis needs additional data analysis to confirm or deny. 

### The differences in weekly bins

We created a new DataFrame with multiple indices and converted it to see the total fare for the date and time:![dates.png](/Resources/dates.png) 

Than we resampled the data in weekly bins and summarized them to get the total fares for each week for each type of cities:

![result.png](/Resources/result.png) 

Here we can see that urban ciities have a biggest amount of data-shering by the week, and rural cities have a smallest amount of data-shering by the week.

### Multiple-line graph

We created a multiple-line graph that shows the total fares for each week by city type^ where we can clearly see the difference: every week urban ciities have a biggest amount of data-shering, rural cities have a smallest amount of data-shering, and suburban cities have amount between two of that.

![PyBer_fare_summary.png](/analysis/PyBer_fare_summary.png)


## Summary: 

Based on the results, we can  make the following business recommendations to the CEO for addressing any disparities among the city types:

* Look for the opportunities to expand the business in rural and suburban cities, including increasing the number of drivers and their rides. 
* Provide opportunities to increase the length of the trip in the urban cities, as examle you can start some city tours or excurtion rides. 
* The elimination of total fires differences can also be ensured by the increasin fares for ride-sharing in rural cities, therefore the lower quantity of rides will proide higher amount of total fires. 
