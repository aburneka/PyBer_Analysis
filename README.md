# PyBer Data Analysis

## Project Overview 

V. Isualize, the CEO of ride share company, PyBer has asked us to create a summary DataFrame of the ride-sharing data by city type. V. Isualize has also requested that we create visuals that will show the total weekly fares for each city by type. Finally, the CEO will require a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

The following data has been provided for each city type, Urban, Suburban and Rural: 
  * City 
  * Date of ride 
  * Fare amount 
  * Ride ID   
  * Driver count 
  * City type 
  
The timeframe for the data was from January 1, 2019 through April 30, 2019. 


## Resources 

* Data Sources:
  * ride_data.csv
  * city_data.csv 
* Software: Jupyter Notebook, Python 3.7.9 and MatPlotLib
* Other Resources for Help with Code:
  * https://matplotlib.org/3.1.1/gallery/color/named_colors.html
  * https://matplotlib.org/3.1.0/api/_as_gen/matplotlib.axes.Axes.pie.html
  * https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.pivot.html

## Overview of the analysis: 

#### PyBer Weekly Fare Summary 

![PyBer_fare_summary](https://user-images.githubusercontent.com/79999761/115161806-812f7480-a054-11eb-931d-5c0ec7df0cd0.png)

## Differences Between Cities 

### Rural Cities 
 As seen in the Summary of Fares by City Type image the average fare per driver and average fare per ride in rural areas is much higher than urban and suburban locations. This is likely due to the length or distance of the rides in rural areas. There are also fewer drivers in rural areas, 78, and would mean less competition for drivers. There are also a fraction of total rides in rural areas. 
 

### Suburban Cities 
The averages for suburban areas lie in between rural and urban locations. There are 
412 more drivers in suburban cities than rural, but 1,915 less than urban. The average fare per ride and average fare per driver are higher than urban, but lower than rural. Also, there are 1,000 fewer rides than urban, but 500 more than rural. 

### Urban Cities

Urban cities have the highest demand with 1,625 total rides, they also have the highest total fares collected, but urban cities also have the highest number drivers, 2,405 and the lowest Average Fare per Ride and average fare per driver. The rides in urban areas are much shorter and the ride-share market is much more competitive for drivers. 

### Weekly Total Fares by City Type

In the image below we can see that the urban total fares increased from January - February of 2019 and then remained pretty consistent from March - April, with a few weeks where there spikes in the total fares. 

Suburban and urban fare totals look consistent over the 4 months in 2019. All three city types have a spike in weekly fare totals in the 3rd week in Februrary. 


#### Summary of Fares by City Type 

<img width="604" alt="Rides by City Type " src="https://user-images.githubusercontent.com/79999761/115161902-0d419c00-a055-11eb-8108-a5e3e6927392.png">


## Reccomendations 

**1. Increasing the cost of rides in urban areas. Beccuase there are so many drivers and the ride distance or length of ride time is much shorter than suburban and urban areas, the prices could be increased to make the average fare per ride and average fare per driver more equitable. 

**2. Having drivers stay in their respective markets instead of edriving to urban areas. Bawsed on the number of drivers in urban areas, these drivers are most likely leaving there homes to drive in urban areas. There must be some sort of perceptioon that they can make more if they are driving in urban areas vs. rural areas, however the average fare per ride and average fare per driver is higher in suburban and rural areas. PyBer could incentivize drivers to drive in different city types, not just urban areas. 

**3. Could also consider technology that wouled allow drivers that do commute to larger cities the ability to pick up rides along there commute. This may cut down on competition in urban areas and allow drivers that commute from other areas to have a variety of ride types - both long and short. This could increase the number of rides and therefore also increase the average fare per driver and average fair per ride. 



## Summary 


