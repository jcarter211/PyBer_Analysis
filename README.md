# PyBer Analysis
## Overview of the Analysis 
In my new role as Data Analyst at Pyber, a ridesharing app company, I am tasked with creating new analyses and visualizations that help the company improve their services. After looking further into the companys..., I created a summary data frame of the ridesharing data broken into city type. I then created a visualization that shows the total weekly fares by city type. The purpose of this report is to explain the different data by city type and to offer guidance to the executives at Pyber based on these differences.

## Results
When creating this analysis, I received two csv files. The first contained the ride data. The second contained the city data. To accurately analyze both, I merged the data into a new data frame. I then found a few different numbers to better help me understand the data: total rides per city type, total drivers per city type, total amount of fares per city type, average fare per ride per city type, and average fare per driver per city type. With these new values, I created a new summary data frame, as seen below. 
<p align="center">
  <img width="800" height="200" src="https://github.com/jcarter211/PyBer_Analysis/blob/main/analysis/summary_df.png">
</p>
As you can see from this data frame, urban cities have the highest number of rides and drivers. Rural cities had the highest average fare per ride and average fare per driver. 
I wanted to continue learning more about each city type and decided to create a multiple line plot that shows the total weekly fares for each type of city. After grouping, reindexing, and creating a pivot table, I was able to create a new data frame that resampled by week. My code is below. 
<p align="center">
  <img width="1000" height="400" src="https://github.com/jcarter211/PyBer_Analysis/blob/main/analysis/sum_weekly_fares.png">
</p>
This code provided the following multiple line plot that allows us to better see the fares per week by city type. 
<p align="center">
  <img width="1000" height="400" src="https://github.com/jcarter211/PyBer_Analysis/blob/main/analysis/Fig8.png">
</p>
Using this graph, we can see that the Urban city type matches our summary data frame and is making the most money. Each city type had a spike in fares towards late February.

## Summary 
Based on the analysis I performed, there are three business recommendations I suggest. 

  * Pyber should focus their marketing efforts on Urban cities, as these make the most revenue for the company. 
  
  * Pyber should try to hire more drives in rural cities. The customers in these cities are spending about $10 more per ride than those in Urban cities.
   If other rideshare companies have a more proportionate amount of drives to rides their prices could be significantly lower, making PyBar less popular.
   
  * Because of the large number of Urban drivers, these drivers make a significantly lower fare than Rural cities. If these drivers become upset about
   the lower fares, PyBer may need to either increase fares in cities to keep those drivers or reduce the number of drivers on staff. 
