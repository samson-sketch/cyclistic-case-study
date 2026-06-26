# Cyclistic Bike-Share Case Study

## Overview
This project is a data analysis case study completed as the capstone 
project for the Google Data Analytics Professional Certificate (Coursera, 2023).

I worked as a junior data analyst for Cyclistic, a fictional bike-share 
company based in Chicago. The goal was to understand how casual riders 
and annual members use Cyclistic bikes differently, and to provide 
data-driven marketing recommendations to convert casual riders into 
annual members.

## Tools Used
- R (RStudio)
- tidyverse, ggplot2
- Data cleaning, transformation, and visualization

## Data Source
Historical trip data provided by Motivate International Inc. 
covering January 2023 – July 2023 (7 months).
Data made available under this license for public use.
Personal rider information was excluded for privacy.

## Data Cleaning Steps
- Combined 7 monthly datasets into a single data frame (Combined_Trips)
- Created a ride_length column from end_time minus start_time
- Converted ride_length from time to numeric data type
- Removed all rows with null values
- Removed entries with ride length less than zero
- Removed longitude and latitude columns (not needed for analysis)
- Combined start and end locations to create aggregate route data
- Ordered months (January–July) and days (Sunday–Saturday)

## Key Findings
1. Casual riders recorded 2,557 more rides than member riders overall,
   but both groups spent similar average minutes per ride.
2. Both casual and member riders peaked in June and hit their lowest 
   point in January.
3. Both rider types were most active on Saturdays.
4. The classic bike was the most used overall; member riders preferred 
   the electric bike. Only casual riders used docked bikes.

## Recommendations
- Run marketing campaigns between June and July when bike usage peaks
- Target casual riders with ads from noon to evening for maximum reach
- Introduce a rewards program that incentivizes long rides with points 
  exchangeable for membership discounts

## Full Write-Up
Read the complete case study and analysis on Medium:
https://medium.com/@awopetusamson1/data-project-cyclistic-case-study-33c1b40cae6c
