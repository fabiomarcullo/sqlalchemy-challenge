# Sqlalchemy Challenge

## Background
Congratulations! You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii. To help with your trip planning, you decide to do a climate analysis about the area. The following sections outline the steps that you need to take to accomplish this task. 

## Technologies Used
- Python
- SQLAlchemy
- Pandas
- Matplotlib

## Objectives

1. Data analysis and exploration
2. Flask API design

## Part 1: Analyze and Explore the Climate Data

In this section, you’ll use Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database. Specifically, you’ll use SQLAlchemy ORM queries, Pandas, and Matplotlib. To do so, complete the following steps:

### Precipitation Analysis

![precipitation_bar.png](https://github.com/fabiomarcullo/sqlalchemy-challenge/blob/main/Images/precipitation_bar.png)

![precipitation_stat.png](https://github.com/fabiomarcullo/sqlalchemy-challenge/blob/main/Images/PreciptationStat.PNG)

### Station Analysis

#### Station Analysis: The most recent date in the data set is 2017-08-23.
The station with the highest number of observations is station USC00519281, with 2772 observations as shown with the observation count in descending order.


![TemperatureStatistics.PNG](https://github.com/fabiomarcullo/sqlalchemy-challenge/blob/main/Images/TemperatureStatistics.PNG).

![StationAnalisis.PNG](https://github.com/fabiomarcullo/sqlalchemy-challenge/blob/main/Images/StationAnalisis.PNG).

![TempStation.PNG](https://github.com/fabiomarcullo/sqlalchemy-challenge/blob/main/Images/TempStation.PNG).

![histogram_tobs.png](https://github.com/fabiomarcullo/sqlalchemy-challenge/blob/main/Images/histogram_tobs.png)


## Flask API Design
Design a Flask API based on the queries that were developed during the climate analysis. 

NOTE: dependencies and set-up were identical to the climate analysis overview except for the engine and session creation. 

