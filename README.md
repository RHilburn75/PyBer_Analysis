# PyBer_Analysis
## Overview of the Analysis
 With our enhanced skills, in Python and Pandas, Omar and I were given a brand new assignment.  V. Isualize wants a summary of our analysis.
Using our resources we'll create a summary of ride sharing data by city type, using data frames. Then, using Matpltlib, we'll create a multiple line chart that will show the total weeklyfares for each city type.
## Development Platforms

 - Jupyter Notebook
 - Python v 3.7.6
 - Pandas library
 - Matplotlib Library

## Resources
 - ride_data.csv
 - city_data.csv

## Summary
We'll 1st look at the summary Dataframe from our threes types:

![image](https://user-images.githubusercontent.com/94253815/147363389-c7029d15-549b-4dd7-ae7b-c70029af9976.png)

- Total Rides - 2375
- Total Drivers - 2973
- Total Fares - 63,538.64
- Avg Fare - $30
- Avg Fare per Driver - $37.2

#### Rural
 - Total Rides - 5.2% of total / 2.6% of total drivers / 6.8% of total fares
 - Avg fare per ride is the highest of the three
 - Avg Fare per driver is also the highest of the 3
#### Suburban
 - Total Rides - 26.3% of total / 16.4% of total drivers / 30.4% of total fares
 - Avg fare per ride is the middle of the road of the 3
 - Avg Fare per driver is also the middle of the road of the 3
#### Urban
- Total Rides - 68.4% of total / 80.8% of total drivers / 62.7% of total fares
 - Avg fare per ride were the lowes
 - Avg Fare per driver were the lowest

The data was scrubbed even further, removing al NaN data, and focusing on a specific timeframe - 01/01/19 to 04/28/19.  Here's the results of sum of fares per week:


![image](https://user-images.githubusercontent.com/94253815/147364743-cc8e3152-127e-4894-96fd-c2535c3ce429.png)

To visualize the data, We created a line chart to reflect the above data:

![image](https://user-images.githubusercontent.com/94253815/147364919-2e7b43aa-a8e4-40d1-bac9-90c6862a413f.png)

## Summary

 Population in these three area directly impact the data found. With a denser population in the urban areas, people tend to use rideshares more often due to congestion in the cities.  Witht he amount drivers and volume of rides, it helps keep cost low.  Shorter drives and more riders sharing rides impact the cost as well.
  Lookig at the surburban data, ride es are in the middle of the road.  This could be due to people moving to the suburbs to raise families.  More people have their own vehicle.  There are more ride shares as people may use this mode of transit to go to work, avoid using their cars.
   Finally, the rural areas tend to have less rides, less drivers but higher fee.  More rural areas could be seperated by larger distances which will drive up the overall cost.  More people may als be more dependant on their own form of tranportation
### Business Recommendations
1. utilize more drivers in each area.
 - More urban drivers working in the suburban areas
 - More suburban drivers working in the rural areas
2. Increase the wage in the suburban and rural areas 
3. Develop areas where drivers work.  Map out certain areas and have drivers assigned to those areas

