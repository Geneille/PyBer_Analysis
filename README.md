# PyBer_Analysis

## Overview and Objectives

Bike ridesharing data was collected for different cities and needs to analyzed. The data, categorize based on city type (rural, urban, and suburban), can be used to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. The purpose of this project was:
* to produce a summary report of the ride sharing data by city type, including total drivers, total rides, total fares, average fare per drive and average fare per driver. 

* to create a multiple line graph that shows total weekly fares by each city type. 

## Resources
1. The data files used in the analysis include city_data.csv and ride_data.csv.
2. Python and Jupyter notebook
3. Pandas and Matplotlib libraries

## Results 

The table below summarizes the data according to city type. The following observations can be made

* Rural cities have the least amount of drivers, rides and total fares while urban cities have the most within each of these categories. 
* In contrast, rural cities have the highest average fare per ride and fare per driver while urban cities have the lowest average of fare per ride and fare per driver.

Table 1

<img width="385" alt="Screenshot 2021-12-05 174013" src="https://user-images.githubusercontent.com/92636438/144766777-2ec8e24f-cc1c-4872-ad4b-ff1a63a13d8a.png">

Figure 1 below shows how the fares for each city type varies across the months January to about May. Clearly, urban cities have the highest total fares whereas rural cities is consistently the lowest. There is a stark contrast in the total fares between the city types. Rural cities accumulates approximately $4,000, ranging from a low of about $70 to a high of about $500, whereas urban cities accumulates approximatey ten times more (about $40,000) over the same period considered, ranging from about $1,700 to $2,400. Suburban cities tallies about $20,000 ranging from a low of about $700 to a high of about $1,400.

A noteworthy observation that can be made for each city type is that the total fares are fairly consistent across the months considered. In other words, although there are some fluctuations, which is expected, there is no major deviation or spikes. A regression line through these graphs would produce a small slope. However, there is a spike toward the end of February for the Suburban cities and this needs to explored further.

Figure 1.

![PyBer_fare_summary](https://user-images.githubusercontent.com/92636438/144766806-71926722-5b3f-485d-aad0-f9e64bc9e40e.png)

  
## Summary and Recommendations

The data indicates that the demand for drivers is higher in the urban areas therefore it is within expectations that the total number of drivers and hence total fares accumulated there is higher. Suburban areas falls second to the urban areas in these categories followed by the rural city type. However, with more drivers the average fare per driver for the urban areas is the lowest at approximately $16 with the highest average fare per driver of approximately $55 being credited to the rural areas. Based on these observations, the following recommendations can be made:

1. Explore the data (further) by city, rather than just city type as done in this analysis, to see where the drivers can be relocated to increase their average fare. In other words, is there any particular city where the demand is not being meet that resources could be either permanently or temporarily diverted? 

2. The ratio of total rides to total drivers is approximately 67%, 127%, and 160% in urban suburban and rural city type, respectively. This means that there is room to restructure and relocate drivers, either periodically/temporary, from the urban cities to the suburban and rural cities. 

3. Increase the fare per mile in the urban cities. Drivers in these cities earn the lowest since it is highly likely trips are shorter. So, although the demand is higher in the urban cities the length of the trips is also likely shorter and with so many drivers the average fare per driver is lowest because drivers don't earn as much per trip. 

4. From Figure 1 above, as previously mentioned, there is a spike towards the end of February for suburban cities. The data here needs to be explored further to determine if this is an anonmaly, or if there is a particular reason for the increase in fares, such as an event, that can be exploited further by say providing more drivers around this time to increase profits.
