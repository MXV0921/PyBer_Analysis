# Pyber Ride Share Analysis

## Overview of Analysis Project
In this analysis project we were given two CSV files.  These files were raw data from a company 'PYBER' and the two files gave us information about different aspects of data but they shared one common category.  We utilized the Pandas function of Python to merge the two files into one DataFrame.   

![Merging Files](https://github.com/MXV0921/PyBer_Analysis/blob/main/Resources/Merged_DF.png)

We then used the 'groupby' function of Python to sort our DataFrame and focus on various datapoints.  We sorted the data into three categories of types of cities, Rural, Urban, and Suburban.  Through the rest of the project we were able to give comparisons between these city types, and provide statistical analysis for across various cross sections of the data.

Utilizing the matplotlib library function within Python we were able to create various charts and graphs that help a reader to understand the data that we are presenting.

## Results of Analysis

### Average Fare by City Type (Scatter Plots)

![Ride Sharing by City Type](https://github.com/MXV0921/PyBer_Analysis/blob/main/Analysis/Fig1.png)

Above is a scatter plot of rides per city type and the average fare for each city.  Each point on the plot is a city location.  The larger bubbless seen representing Urban cities denote more rides in each city with a lower average fare.  Smaller points on Rural locations denote less rides at a higher average fare.

### Number of Rides per city by City Type

![Rides per city by city type](https://github.com/MXV0921/PyBer_Analysis/blob/main/Analysis/Fig2.png)

This next chart shows is a box and whisker plot.  It gives a good representation of the average amount of rides per city within each city type.  Box and whiskers also show any data that is an outlier.  In this dataset there is one outlier in an urban city that has a much higher ride count than the rest of the set.  Similar to the scatter plot, this shows that urban cities have more rides per city than the other city types.

### Pie Charts to Further Explain

![% of Total Fares by city](https://github.com/MXV0921/PyBer_Analysis/blob/main/Analysis/Fig5.png)

We created a pie chart to show the percentage of fares by city type.  Urban cities account for almonst 2/3rds of the total fares taken in.

![% of Rides by City Type](https://github.com/MXV0921/PyBer_Analysis/blob/main/Analysis/Fig6.png)
This pie chart represents the total ride count take in.  Urban rides also represent over 2/3rds of the total rides taken. 

### Line Charts to Show Fare Summary

![Total Fare by City Type](https://github.com/MXV0921/PyBer_Analysis/blob/main/PyBer_fare_summary.png)

Python has a function known as resampling, we were able to convert our data into a weekly summary.  

![Resampling]

The line chart we created shows the fares per city in USD over a 4 month period in 2019.  Urban cities showed an increase each week during January and then continued to fluctuate but remain fairly consistent through the next three months.  The other city types have a negligible change in fares over the 4 month period.

## Summary and Recommendations
1. Urban cities have the highest amount of rides taken and are responsible for the largest amount of income for the company.  Rides here have the lowest average fare, and the largest amount of drivers.  Focusing on a marketing plan in urban cities to grow this part of the business would not require much infrastructure to be successful.
2. Rural Cities have the highest per fare average in price but the smallest amount of rides taken of all the city types.  We should investigate the cause for such low amount of usage of our company.  Is there a low demand for rides or are we charging too much for each ride? 
3. We should investigate more into the line chart that was created.  4 Months is a very small data sample and we should look at this over a longer period of time.  If we were to look at this data over multiple years we could see a better trend of the growth of our company.
