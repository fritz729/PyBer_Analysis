# PyBer_Analysis


## Overview

This project is looking at the data collected by the ride sharing company PyBer to review trends on the ride data collected. Our mission is to provide the CEO with insight into ride revenue in different city times which include urban, suburban, and rural cities. This data can help determine the strategies for the company moving forward on how resources are allocated and develop metrics that can be used to measure the performance of the drivers in each type of city environment. These datasets were analysed using Pandas and JupyterLab to clean and sort the data to create visuals to represent the trends observed in the data. 

---

# Results

## City Type Analysis

Using the merged dataset, each city within the territory was characterized as being one of three city types: Rural, Urban or Suburban.  The data for each city was grouped by city type and allowed for the analysis trend on the rides conducted in each city type.  An overview of the data can be seen in the table below which gives a broad summary of the ride data that was collected for this analysis.



### Urban City Type:

The data from the urban city types showed that there were a greater number of rides and overall ride revenue from these areas.  There is the largest number of drivers and the highest fare revenue observed from the rural cities. There is also the highest number of rides overall from the urban cities.  The urban centers also have the lowest average fare and the lowest average fare per driver. 

### Suburban City Types:

The suburban city types fall between the urban and rural city types.  They have a moderate number of drivers and rides and the average fare and average fare per driver falls between the rural and urban city types.  There is higher increase in the average fare per driver between the urban and suburban drivers, with the suburban drivers making 138% more per ride that that of the urban drivers.  This with only a 26% greater in average fares in the suburban cities versus the urban cities. 

### Rural City Types:

The rural cities have the lowest ride and driver numbers with the lowest fare revenue of the other two city types.  Conversely, the rural cities have the highest average fares and average fare per driver than the other areas.  The rural cities have 5x less drivers that the suburban cities and 13x less drivers than the urban cities.  The rural drivers however earn 234% more in average fares than the drivers in the urban centers with only a 41% greater average fare than their urban counterparts.  

### Overview of the data

From an analysis of the week-by-week rides from each of the city types, a line graph was created to show the relationships between the frequency of rides between each of the areas.  As seen in the figure below, there is a similar variation in the total fares collected from the rides across the rural and urban cities.  The suburban cities appear to have a more consistent number of rides over time.  This there is similar trends observed in late February across all the cities, but the overall trends appear unique to each area.  There is a consistency of the overall amount of ride revenue collected in each city type over time which is reflected in the overall rank of each city in the overall data. 



A further analysis of the data using a scatterplot shown below, illustrates the clustering of the rides by city in comparison between the number of rides and the average fares.  This data set shows that there is a larger concentration of the rides in the urban city groups but a lower overall average fare per city.  There does appear to be some crossover between the number of rides between the suburban and urban city types however the suburban average fares are distinctly higher in this crossover area.  The rural city types are generally show a consistently lower number of rides and a consistently higher average fare.



Finally, an analysis of the distribution of fares between the city types showed that there was a consistent range of fares between the urban and suburban city types, with a large range of fares observed in the rural city types.  This is illustrated in the boxplots that are shown below that present the distribution of the fares between the three city types. 


---

## Summary
