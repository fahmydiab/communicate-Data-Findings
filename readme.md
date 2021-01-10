# (Fordbike Feb. 2019 Data Exploration)

## Dataset

> The dataset contains the information for the Fordbike Data for users in Feb. 2019 .
First, the exploratory data analysis on the dataset.To understand the data structure ,i will use necessary Python data science and data visualization libraries to explore the dataset features , anomalies, patterns and relationships. 
The analysis in this part is going from univariate relationships up through multivariate relationships. 

> This document explores a dataset containing the trip data of the ford gobike for one month (Feb. 2019) with features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). Most variables are 9 numerical, and others are 2 datetime, 4 object type and 1 is boolean type.

> Then, I will use findings from exploration analysis and interpret them into others through an explanatory analysis. 
Finally, I will create a slide deck that is plot polished, explanatory visualizations to communicate my results.

> For cleaning the dataset :
> 1- change the data type for start_time and end_time to datetime64.
> 2- change the data type for bike_share_for_all_trip to be bool.
> 3- remove the rows with null values.
> 4- create columns for start_time_day, start_time_month, start_time_hour, duration_minute. 
> 5- checking for ages with more than 100 years old to be cleaned

## Summary

> Trip Duration have a strong relationship with the age of the users, when age is between 20 to 40, the trip duration is higher than the older ages.
> For subscribers the trip duration is higher for older age.
> Both Males and Females share similar trends for age and trip duration.
> Males's trip durations are shorter than those of Females and other gender.
> Highest number of trips are of durations (0-10) mins and the average duration for trips are 11 mins.

