# Exploratory and visual analysis of the FordGo bike system for the year 2019
## by Leon Hamnett


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area for the year 2019. We can see start and end times and dates for each ride, as well as the start and end station as well as the type of user who is using this service.

This analysis will try to discover trends in this data via univariate,bivariate and multivariate visualisations and then use these trends to provide actionable insights for the company for improvments to their business model.

We have obtained data for the bicycle service for the 12 months in 2019. As we have a CSV file for each month, we will read all the file into separate dataframes an then we will combine them all together. 

We than limit the datset to only rows for San Francisco City Area. We also set the datatypes for ease of analysis and create some new columns with variables of interest.

Our final dataset has  1852745 rows and 15 columns.

1) We want to look at the usage patterns of bikes on a variety of timescales including by year,by month,by day of month,by weekday and by hour.

2) We want to look at the journey duration to see how long users are riding a bike for.

3) We want to see if the usage patterns are effected by whether a user subscribes to the bike sharing service or simply is a "pay-as-you-use" customer.

4) We would also like to check the most popular start and end points and to check the number of journeys made between popular bike stations.


## Summary of Findings

We see for all when looking at time periods for year and day of month, the average journey duration for user type Subscriber is pretty consistent staying level around 10 minutes with no major peaks or troughs.

As we zoom in on the timescale and look at day of week and hourly timescales, we see there is a greater amount of variation. However this variation is amplified when looking at Customer users who have a maximum variation of 25 minutes ride duration. We see suprisingly that the peak ride duration for both types of users is in the early hours of the morning. Showing users tend to on average, ride the bike for longer periods early in the morning. Additional market research could be performed to understand this trend in behaviour and a monetisation strategy developed to maximise income from users riding during these times.

We also got a good understanding of the most (and least) popular bike stations to depart and arrive from and we were also able to visualise the most popular routes between the popular start and end stations. The company could use this information to ensure there are sufficient bikes during peak times and could also optimize their bike redistribution path to ensure bikes will be redistributed as evenly as needed, whilst minimising fuel and labor costs associated with redistributing the bikes.

## Key Insights for Presentation

We observe usage patterns between the different user types for time periods of weekday and hour. We also look at the most popular stations and look at the most popular journeys between stations.
