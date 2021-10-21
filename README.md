# Bike Share Case Study

This was my first data analysis project R.
It was my capstone project for the Google Data Analytics Specialization Course on Coursera

### Table of Contents

1. [Libraries Used](#libraries-used)
2. [Goal](#goal)
3. [Data](#data)
4. [Workflow](#workflow)
5. [Conclusion](#conclusion)

### Libraries Used 

library(dplyr)
library(ggplot2)
library(hrbrthemes)
library(hablar)
library(lubridate)
library(hms)
library(scales)
library(leaflet)
library(mapsapi)
library(htmlwidgets)
library(htmltools)

### Goal 

You are a junior data analyst working in the marketing analyst team at Cyclistic, 
a bike-share company in Chicago. The director of marketing believes the company’s 
future success depends on maximizing the number of annual memberships. 
Therefore, your team wants to understand how casual riders and annual members use 
Cyclistic bikes differently. From these insights, your team will design a new 
marketing strategy to convert casual riders into annual members. But first, 
Cyclistic executives must approve your recommendations, so they must be backed up
with compelling data insights and professional data visualizations.

#### How do annual members and casual riders use Cyclistic bikes differently?

### Data

Cyclistic is a fictional company. The data has been made available by Motivate International Inc. 
under this [license](https://www.divvybikes.com/data-license-agreement)
The data is available [here](https://divvy-tripdata.s3.amazonaws.com/index.html)

Cyclistic has a fleet of 5,824 bikes that are geotracked and locked into a network of 692 stations across Chicago.
Cyclistic Business Model includes flexible pricing plans : single-ride passes, full-day passes, and annual memberships.

### Workflow

1. Preparation
2. Transformation 
3. Analysis
4. Graphs and Plots
5. Report
6. Conclusion
7. Recommendations

### Conclusion

Key Differences between Annual Members and Casual Renters are :

1. Casual Renters, on an average, rent bikes for longer periods of time.
2. 50% of casual renters rides are between 10 to 40 minutes long, whereas 75% of members rides are shorter than 22 minutes.
3. Casual Renters are more active than Annual Members on Friday and Saturdays.
4. During the week Annual Members are more active renters.
5. During the week, a greater number of Annual Members follow a traditional Office hours schedule.
6. Casual Renters are more active over the weekends. Peak hours are in the late afternoon and continue until late night.
7. Casual Renters are concentrated on the waterfront areas and tourist attractions.
8. Annual Members in addition to the waterfront and tourist attractions are also active near residential areas, educational institutes, student hubs and city centres.
9. Casual Renters who are renting for longer than single day tend to keep the bike for an average of 4 days.
10. Annual Members who rent for longer than a day return the bike by around the 25 hour mark.

### Top 3 Recommendations

1. Target those Casual Members who follow a traditional Office hour schedule.
2. Increase presence around educational institutes and areas popular with students.
3. Encourage Casual Renters to rent for shorter lengths and shorter distances.
