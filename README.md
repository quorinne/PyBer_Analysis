# PyBer_Analysis

# Overview of Analysis

We have been asked to analyze data for PyBer, a ride sharing service. We have created several different charts to show the relationship between number of drivers, number of rides, and average fare per city type. The data will then be used to help PyBer improve access to their ride sharing technology determine the affordability in different types of cities.




# Results

## Average Fare Per City Type
Not every type of city will have the same demand for ride sharing services, it would be rather strange if a small town such in the middle of nowhere had as many drivers and rides as a city such as New York or LA. This was made evident during out analysis of the data provided by PyBer. Please direct your attention towards the scatter plot below. 
![alt text]( https://github.com/quorinne/PyBer_Analysis/blob/main/Analysis/Fig1.png?raw=true)

The plot above depicts the cost of fare (Y Axis) and its relationship to the total number of rides per city. As we can see rural areas have a small number of rides while urban areas have quite a bit more. 

### Total Fare Over Time

Total Fare by City Type is also shown in the line chart below as it changes over time. In this chart we notice that all three city types experience an increase in total fare towards the end of February right before the month of March.  We can also see how suburban and rural areas have a fairly stable level of total fare from March to April while Urban areas see the total fare rising and falling in larger increments more before April. 
![alt text]( https://github.com/quorinne/PyBer_Analysis/blob/main/Analysis/Del2.png?raw=true)




## Drivers Per City Type
Another interesting trend to notice with this plot is that the average fare is higher in rural areas likely to the limited number of drivers. If the supply is low cost will rise. 

![alt text]( https://github.com/quorinne/PyBer_Analysis/blob/main/Analysis/Fig2.png?raw=true)

The box plot above depicts the total number of drivers per city. As we can see urban areas have the largest number of drivers by far with rural areas having the fewest. A better way to showcase this information is with a pie chart or in the data summary. In the Pie chart below we can see that urban areas have 80.9% of drivers while rural areas have 2.6% and suburban areas have 16.5% of drivers.  
![alt text]( https://github.com/quorinne/PyBer_Analysis/blob/main/Analysis/Fig7.png?raw=true)

The actual number of drivers, rides and fare per city type is shown in our Data summary below.  

![alt text]( https://github.com/quorinne/PyBer_Analysis/blob/main/Resources/Summary_DataFrame.png
?raw=true)

In this data summary we can see that there are 78 drivers for only 125 rides in rural areas while suburban areas have 490 drivers for 625 rides. Urban areas meanwhile have a total of 2,405 drivers for only 1,625. They have 67.6% more drivers than actual rides. The supply of drivers is high while the demand for rides is low. 

## Total Rides Per City Type

If we compare the percentage of drivers against the percentage of total rides per city type in the chart below, we will see a similar distribution. With urban areas having 68.4% of total rides by city type and rural 5.3% and suburban areas finishing off the pie with 26.3% of total rides. While not a perfect match to the percentage of drivers by city type it still showcases the higher demand for ride sharing services in urban areas. Rural and suburban areas having a small increase is likely due to the lack of public transport available such as buses or subways which we see more of in cities with larger populations. 
![alt text]( https://github.com/quorinne/PyBer_Analysis/blob/main/Analysis/Fig6.png?raw=true)

The percentage of total fare by city type is closer to the percentage of total rides per city type than drivers per city type. As seen in the chart below urban areas have 62.7% of total fare, suburban has 30.5% and rural has 6.8%. This is likely due to the increase in drives in urban areas. As supply increases cost is lowered and more potential riders can use public transportation if the cost gets too high. 
![alt text]( https://github.com/quorinne/PyBer_Analysis/blob/main/Analysis/Fig5.png?raw=true)



# Summary
As seen throughout this analysis the supply of drivers and total number of rides is far larger in Urban areas than rural or suburban areas. While the average cost of fare per ride is higher in rural areas when compares to urban areas. This is likely due to higher demand of ride sharing services proportional to the population in rural and suburban areas. In fact, there are too many drivers in urban areas with 67.6% more drivers than rides many of the drivers will be unable to pick up a single fare. 
One possible solution would be to try and encourage urban drivers to move to more rural and suburban nearby areas. This will increase the supply of drivers in those areas and increase the number of drivers able to pick up fares. 
Another solution would be to lower the cost of rides in urban areas. If rides are more affordable then more people will opt for ride sharing services as opposed to public transportation. 
Of course, the average fare per ride is already lower in urban areas so lowering the cost further may prove detrimental to the drivers. Which leaves us with the problem of there being too many drivers in urban areas. One potential solution would be to make the PyBer ride sharing service a more attractive alternative to the cheaper public transportation. Our greatest selling point in here is speed. It is easy to justify an extra $15 spend on weekend and an extra $5 on weekdays if the wait for a driver is much shorter than the wait for a bus or subway. Perhaps if PyBer started assigning areas to drivers. If Neighborhood A and Neighborhood B both have ten drivers, but Neighborhood A has 7 people waiting on rides and Neighborhood B has 13 people waiting for rides then it makes more sense for Neighborhood B to have more drivers. The drivers may not realize this themselves so if PyBer assigns neighborhoods like the city assigns bus routes it could decrease the time spent waiting for a ride and increase the likelihood of returning to the ride sharing service. 



