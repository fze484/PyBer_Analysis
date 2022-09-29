# PyBer_Analysis


## Overview of the analysis: 

Using Python and Pandas, I’ll create a summary DataFrame of a ride-sharing database by city type for a company called PyBer,which wants to assess the ride-sharing market in 3 different cities: Rural, urban and semi-urban. Then, using Pandas and Matplotlib, I’ll create a multiple-line graph that shows the total weekly fares for each city type. The goal is to summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer.


## Results: 

According to the summary dataframe: 
* Urban areas make up 62% of the total market (total fares)
* Suburban areas make up 30% of the total market (total fares)
* Rural areas make up 7% of the total market (total fares)

Additionally, there is a lot more supply in drivers in urban areas: 
* 111 times more drivers in urban areas compared to rural areas;
* 13 times more rides in urban areas compared to rural areas;

Because there is a higher supply in urban areas as compared to rural and suburban areas: 
* Average fares per ride are $10 higher in rural areas as compared to urban areas and nearly $4 higher when compared to suburban areas
* Average per driver is about $8 higher in rural areas as compared to urban areas and nearly $6 higher when compared to suburban areas

**Summary dataframe: **

<img width="590" alt="Screen Shot 2022-09-28 at 22 04 13" src="https://user-images.githubusercontent.com/80678332/192921987-2bbe2142-7460-4389-8137-74e1a6a6ff80.png">


Looking at the seasonality chart of ride fares in USD: 
* There is a price peak around the end of Feb for all 3 areas;
* Starting mid April, there is a decrease in ride fare in urban and rural areas;
* The opposite trend is observed for semi-urban areas: We notice an increase in fares around the same period.

**Summary seasonality chart: **

<img width="989" alt="Screen Shot 2022-09-28 at 22 05 34" src="https://user-images.githubusercontent.com/80678332/192922117-122f8ec7-dcc7-445f-948f-3b586d23c532.png">

## Summary: 

Based on the results: 
* PyBer should capitalize on the lack of driver supply (and competition) in rural areas. The fare per ride and per rider are much higher in this area as well and can generate higher profits. 
* The company should take advantage of the peak in seasonality at the end of Feb and look into deploying more drivers around this time of year;
* Deploy drivers to cover the suburban areas around the end of April, as this may be a migration period where people in rural areas and cities go to the suburbs as summer approaches. 
