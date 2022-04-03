# PyBer_Analysis

## Overview

### History
The previous analysis was performed on large datasets of the PyBer ride-sharing app. company. Several types of visualization charts were created to demonstrate the relationship between the city types, number of drivers and riders, total fares, and riders and drivers by city type. 

### Purpose of the Analysis
In this project, the same datasets were studied to analyze ride-sharing data by type of city and a multiple-line visual chart was created to represent the total weekly fares based on the city types.

The result of the analysis will help understand how data varies by city type and how these differences can be applied to improve company- decisions in the future. [PyBer_Challenge](https://github.com/duygusimsek/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

## Results
A statistical overview and summary were created by using both datasets.[city_data.csv](https://github.com/duygusimsek/PyBer_Analysis/blob/main/Resources/city_data.csv),
[ride_data.csv](https://github.com/duygusimsek/PyBer_Analysis/blob/main/Resources/ride_data.csv)

In this analysis;
* For each city type total rides, total drivers, the total amount of fare, average fare per ride, and average fare per driver were obtained from the datasets. 
* By using these findings PyBer summary data frame was created. ![PyBer_summary_df](https://github.com/duygusimsek/PyBer_Analysis/blob/main/analysis/PyBer_summary_df.png)
* According to the PyBer summary table, due to the high demand for ride-sharing in Urban cities, the Urban cities have the highest total riders and total drivers compared to Suburban and Rural cities.  [Total Drivers by City Type(%)](https://github.com/duygusimsek/PyBer_Analysis/blob/main/analysis/Fig7.png)
* Rural cities have the lowest ride-sharing demand. [Total Rides by City Type(%)](https://github.com/duygusimsek/PyBer_Analysis/blob/main/analysis/Fig6.png)
* Because of the great usage of PyBer in Urban cities, the total fares are also higher than the other city types. It is approximate 2x times larger than Suburban and  9x times larger than Rural cities. [Total Fares by City Type(%)](https://github.com/duygusimsek/PyBer_Analysis/blob/main/analysis/Fig5.png)
* For Rural cities costs of average fare per rider and per driver are highest than the other type of cities’ averages. 
* "Total Fare by City Type" multiple line charts help to visualize the data from the summary data frame for the three types of cities between January and May 2019. [PyBer_Fare_Summary- Line Chart](https://github.com/duygusimsek/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
* The yellow line represents Urban cities’ total fare change, the red line shows Suburban cities’ change in total fare amount, and the blue line displays Rural cities’ trend in the total fare amount through the months. 
* The multiple line chart shows that all the three city types’ total fare reached their peak point by February 2019. 
* It is clear that the number of rides for Urban cities is significantly larger than the other city types and that shows ride-sharing is more common to use ride-share in Urban city life than in Suburban and Rural cities. This can simply be because of the number of business places, the number of restaurants, nightlife, the large population, economic disparities between different regions, etc. 
* Adding more data to the analysis, we can have a deeper understanding and finer results. 

## Summary
Based on the analysis result, some business recommendations for Pyber are;
* With additional data, the pickup locations can be determined, and for busy locations and hours, the driver numbers can be increased. 
* The Rural cities’ driver numbers can be increased. This can help to reduce long-distance traveling and increase to meet ride demand. 
* Affordability will increase the ride demand, especially for low socioeconomic cities. By decreasing the fare by ride, the low-income areas’ ride-share demand can be increased. 

## Resources
* Data Sources: [city_data.csv](https://github.com/duygusimsek/PyBer_Analysis/blob/main/Resources/city_data.csv),
 [ride_data.csv](https://github.com/duygusimsek/PyBer_Analysis/blob/main/Resources/ride_data.csv)
* Software: [Jupiter Notebook 6.3.0](https://jupyter.org/)
* Language: [Python 3.10.2](https://www.python.org/downloads)
* Libraries: Pandas and Numpy, Matplotlib 





