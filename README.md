# PyBer_Analysis

Pyber Ride-Sharing Analysis using Pandas, Jupyter Notebook and Matplotlib 

## Purpose

* **Create line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib.**
* **Add and modify features of Matplotlib charts.**
* **Add error bars to line and bar charts.**
* **Determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.**

## Overview of the analysis: 

PyBer, a python based ridesharing app company wants to perform an exploratory analysis and visualization on a large ride sharing data to establish a relationship between type of city and number of riders, drivers and fares and percentages of each city type in total fares, total rides, and total drivers. This will help PyBer improve the access to its ride-sharing services and determine affordability in different city types. 
With the knowledge of Python script using Pandas library, Jupyter Notebook, and Matplotlib we will create variety of charts to showcase important findings. 

Softwares Used: Anaconda, Conda, Jupyter-Notebook, ipykernal, Python, Pandas, Numpy, Matplotlib, GitBash 

## Results

### Number of Rides and City Type

Number of Rides is the highest in Urban city type ranging from 21 to 28. Whereas in Rural city type, it ranges from 5 to 9. Suburban city type rides are from 14 to 19. This shows that Urban city type is best suitable for ride sharing services for PyBer with maximum number of rides and Rural is the least desirable type here. 
![image](https://user-images.githubusercontent.com/108366412/182763223-44f01642-5b51-41b8-ac3b-5644f67c4816.png)
 
The below pie chart also supports our findings about Urban city type being the biggest contributor. 68.4% out of the total rides were in Urban whereas only 5.3% of rides were Rural type of cities. Suburban cities had a share of 26.3% of the total rides.
![image](https://user-images.githubusercontent.com/108366412/182763270-98884bfa-bba3-4d85-88ef-2bcacf802922.png)

### Driver Count and City Type

Number of Drivers in Urban cities is maximum ranging from 22 to 52. And that is Rural cities is the least which is from 1 to 7. Suburban cities are in the middle with a range of 5 to 21. This is the same pattern we saw in the previous relationship (city type and ride count). This shows the number of drivers in each city supports the number of rides which are high Urban city and low in Rural city. 
![image](https://user-images.githubusercontent.com/108366412/182763321-963ad2a8-0ae9-426f-9925-91b29ce2d1a9.png)
 
The above statement can also be concluded with the following pie chart which shows that out of total number of Drivers, 80.9% of drivers are in Urban cities whereas 16.3% are in Suburban and only 2.6% are in Rural cities.
![image](https://user-images.githubusercontent.com/108366412/182763338-d0161a5d-1219-4a3e-bbf1-fe5963283350.png)
 
### City type and total Fares

The average fare in Urban cities ranges from 15 to 35 which is the least as compared to Suburban and Rural which are from 22 to 40 and from 20 to 47 respectively. Important thing to note here is that although the average fare is low in Urban cities, percentage of total fare collected from its transactions is highest among all city types. This is due to very high number of rides. 
![image](https://user-images.githubusercontent.com/108366412/182763373-6bcf79d8-4865-43f8-839f-bf045db25887.png)

The pie chart below shows Urban cities has the highest total fares percentage at 62.7% and Rural with the lowest percentage at 6.8%
![image](https://user-images.githubusercontent.com/108366412/182763415-450071f0-be5b-4eb0-b19c-5a1da98b982c.png)

### Summary Report

The figures discussed can also be seen in a summary table below. Out of the 2375 total rides, 1625 rides are in Urban cities and only 125 in Rural cities. Similar is the situation with total drivers. 2405 drivers are in Urban cities and only 78 in Rural cities. Looking at the average fare per ride and per driver, both are higher in Rural cities at $34.62 and $55.49 respectively as compared to Urban city average which are at $24.53 and $16.57 respectively. However, due to high volume of rides, total fare is still high in Urban cities at $39854.38
![image](https://user-images.githubusercontent.com/108366412/182763448-fe90bf2f-718f-4a18-aadc-a0b017c10a1b.png)

The scatter plot below will provide a visual image of summary of total number of rides (x_axis) by Averege Fare (y_axis). The circle size shows the driver count per city. Rural circles are few, small and lies high in the chart. On the other hand, Urban circles are more in number, big in size and lies low in the chart. Suburban circles are in middle of the chart with medium sized circles. 
![image](https://user-images.githubusercontent.com/108366412/182763493-cbf4ed49-7957-49b8-9d6d-555221f74ba7.png) 
 
The multi-line chart below showing weekly summary of total fares by city type from January to April further supports our findings from the summary table and scatterplot. The total fare of Urban cities ranges from $1662 to $2466 on a weekly basis owing to high number of rides and drivers. As opposed to the Urban cities, total fare for Rural cities on a weekly basis ranged from $68 to $501 due to low number of rides. Suburban cities total fares lie between $721 and $1413. Graph for all the city types moves in the same direction with a peak in fares coming in the last week of February. 
![image](https://user-images.githubusercontent.com/108366412/182763545-4727ea36-e7f1-4784-a5ff-c5972392bd5c.png)
 
From the results we can conclude that in Urban city, number of rides and drivers is high but average fare per ride low. This can be due to shorter distances within the city and/or supply of drivers in abundance leading to low fare per ride. Rural city has high average fare per ride which can be an indicator of long distance rides and/or less supply of driver.


## Recommendations to the CEO of PyBer

* Drivers should be proportionately allocated based on the demand for rides for PyBer to effectively use its driver and for the driver to earn more
* A new attribute distance travelled in each ride should be added to the summary. This will help PyBer determine fare based on distance travelled and also help drivers with higher remuneration.
* Number of people sharing the ride should be given importance. Higher the ride-sharing count, higher should be the fare to increase the average fares in Urban cities.
