# Ford GoBike System Data Exploration
## by Michael Utomi Ehiabor


## Overview

> Ford GoBike System Data Exploration: This document explores a dataset with information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in 2019



## Dataset

The data consists of information regarding 183,412 rides in a bike-sharing system covering the greater San Francisco Bay area in 2019. There are 183,412 rides in the dataset with 16 features ('duration_sec','start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude', 'start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'member_birth_year', 'member_gender', 'bike_share_for_all_trip'. After some data cleaning and feature engineering, tbe dataset was reduced to 11 Columns and the new columns were:
day_of_week: to store week day number from start_time. start_hour: to store hour number from start_time. time_of_day: to store the time of the day from start_hour trip_duration: to store the duration in minutes. user_age: to store the user's age from member_bith_year. age_group: grouped ages to explore information about the different age groups


## Summary of Findings

Subscribe and Customer bike usage was different

> The day of the week that most trips are taken "Thursday" does not depend on if a user is a subscriber or a customer. It was discovered that Subscribers mostly used bikes on workdays (Monday - Friday), while customers bikes usage was about the same for the whole week with a significant rise on Saturday and Sunday On average, Subscribers' trips mostly last for 10.7 minutes, while customers mostly last for 23.9 minutes. On Average,Customers had longer rides on average than Subscribers for every day of the week with Sundays and Saturdays being significantly higher than the rest of the week days. 

## Key Insights for Presentation

I focused
on just looking at the time of the day and the day of the week that most trips are taken.

Average trip duration for Constumers and Subscribers

Check if the results depend on if a user is a subscriber or a customer

The presentation showed that there indeed is a dependency of the average trip duration on if a user is a subscriber or a customer. On average, customers rides lasted longer than subscribers rides on every day of the week and time of the day

