# PyBer Ridesharing Data Analysis

## Overview of Project

### Purpose

The purpose of this analysis was a little different than the previous studies. This time we grouped the ridesharing statistics by the type of city. Using this view of the data, we hope to identify any disparities in the city types overall, or over time.

## Results

Based on the Summary DataFrame below, we notice a few things:
* There are significantly more urban drivers than urban rides
* The average ride fare is much higher in suburban and rural cities, this is likely indicative of the average distance travelled in these areas
* The amount of drivers and rides in Urban, Suburban, and Rural cities are definitely uniform to the general population density of these types of cities

![image](https://user-images.githubusercontent.com/17416097/152703957-401e99d8-0cb5-4aaf-a153-d62a4989d84b.png)

You can also see the graph of Time Series data by city type:

![image](https://user-images.githubusercontent.com/17416097/152703923-6e2dca3d-21a2-4a3b-8745-a2e64aa0e23d.png)

It is interesting to look at the seasonality of the fares in these 3 types of cities. Fares from urban rides seem to be very slowly rising into the warmer months, while rural rides seem to be perhaps decreasing towards the end of April. It would be very useful to see further data from the rest of the year.

## Summary

Based on the findings from our review of the ridesharing and geographical data, I would make several reccomendations to the PyBer CEO:

1. Create incentives to bring in more drivers to Suburban and Rural Cities. You could review further the highest performing cities of these types to decide where to explore these.
2. Consider lowering the price per distance in rural areas. If there is less of a barrier to get a ride for the longer distances required, people may be more interested in using your services. Then the amount of rides will increase.
3. Occasionaly send Urban drivers to suburban cities nearby to increase the supply in those cities to better match the demand of rides. Perhaps people don't use PyBer in these areas because it's often not available at the times or routes that they may need
