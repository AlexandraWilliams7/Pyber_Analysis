# Pyber_Analysis
## Overview of Analysis 
### Pyber
The objective for the Pyber analysis was to develop graphs from the pyber ride share data. V.isualize wanted to see how Pyber rides, fares, and drivers where doing based on the city types (urban, suburban, and rural). To complete the task several graphs were created (bow-and-whiskers, scatter plots, and pie charts) to show the relationship between fares, drivers, rides, and city types. 
This was done using Matplotlib, Pandas, Python, and Jupyter Notebook.
### Pyber_Challenge
The purpose of this analysis is to create additional dataframes for Pyber. The dataframes create will dig into the ride share data on fares by city type. The first Dataframe created will showcase the average fares by rides and drivers based on the type of city, Urban, Suburban, and Rural. Next the analysis will graph the data of total fares each week by city type. 
These task will be executed by using Python and Panda skills like the loc method, resample, and pivot functions. The analysis wil be written in Jupyter Notebook. 

## Results
### Pyber 
#### Rides
The graphs for the rides based on city type showed that there are more rides in the urban cities.
The ride counts in the urban cities are 1.4- and 4- times higher than the suburban and rural ride counts, respectively.
 - Ride Count Data 2019
![Fig2](https://user-images.githubusercontent.com/105830665/180008907-a005ea50-8759-4b3e-bbec-10c44cbb517d.png)

The percent of total rides by city type also shows us that urban cities have more rides than suburban and rural. 
The urban total rides is almost 70% of all rides by Pyber. 
 - % of Total Rides by city type

![Fig6](https://user-images.githubusercontent.com/105830665/180009784-b38128cf-40f2-4186-9a60-11aee7d920f0.png)
#### Drivers
The graphs for the drivers also show an increased amount of drivers in the Urban cities. 
The driver counts in the urban cities is 9- times higher than the rural cities.
 - Driver Count 2019
![Fig4](https://user-images.githubusercontent.com/105830665/180011479-ff205de5-170d-45c7-80cc-1c770483cd9e.png)

The percent total of drivers shows the almost 81% of Pyber drivers work in urban cities.
 - % of Total Drivers by City Type
![Fig7](https://user-images.githubusercontent.com/105830665/180011570-466af93b-8bdf-44b1-8b28-c215a1bd4c0a.png)

#### Fares
The graphs gives two different outputs.
The Ride Fare graph shows that rural cities have a higher fare than all other city types.
 - Ride Fare Data 2019
![Fig3](https://user-images.githubusercontent.com/105830665/180018211-86cfbfbe-9459-4f03-b96a-99892863d298.png)

The percent of total fares shows that urban cities have the higher percent, about 63%. This is due the higher ride counts.
 - % of Total Fares by City Type
![Fig5](https://user-images.githubusercontent.com/105830665/180018304-b71150ab-8012-4e94-997a-02fac6415c2e.png)

#### Overall Pyber
The Overall scatter plot shows the while urban cities have the most rides and drivers the average fare is lower. 
The suburban cities are in the middle for all categories. 
The rural cities are the exact opposite of the urban cities, lower rides and drivers but higher average fares. 
 - Pyber ride-Sharing Data 2019
![Fig1](https://user-images.githubusercontent.com/105830665/180018390-b60ada93-0f7a-43a6-a1ca-4de8cfa2c986.png)

### Pyber_Challenge
#### Pyber_Summary
The new DataFrame shows what the previous graphs did.
This Dataframe gives a numerical expression to the graphs. 
The rural cities have the highest average fares for rides and drivers. the suburban cities have more rides than drivers. 
The Urban cities have too many drivers and it shows in the average fares per driver. 
 - Pyber_Summary
![Pyber_chall_chart](https://user-images.githubusercontent.com/105830665/180021397-a5862c82-b611-4065-873f-fc0acc1692c4.png)

#### Pyber_graph
The line graph shows the each week, from January 1 to April 29, 2019, the Urban cities have the highest total fares. Once again
this is do to the amount of rides the urban cities are completing each week. 
 - Total Fare by City Type
![Pyber_fare_summary](https://user-images.githubusercontent.com/105830665/180022548-ff9c81d3-4d78-4e40-8389-ac9e65e189a2.png)


## Summary
The Pyber CEO can use the graph of the weekly fares by city type to assess the business. Here are three recommendations based on the graph and city types.
**1. Rural**
The Company should look into a mileage promotion for longer drives to help increase the number of rides in the rural area.
**2. Suburban**
The number of drivers need to be increased. Suburban cities are usually closer to major cities. 
Pyber would benefit from the increase of drivers to cut the possible wait times.
**3. Urban**
The Number of drivers in the city are almost 1.5 times higher than the number of rides. The market needs to scale back of the driver count.
If the cutback is done the company would see an increase in average fares per driver.