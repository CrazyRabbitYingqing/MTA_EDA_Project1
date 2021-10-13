# EXPLORATORY DATA ANALYSIS - MTA SURVEY PLAN

By: Yingqing Qiu

### Abstract

The NYC DOT and MTA transit system wanted to construct several new stations to satisfy the growing post-pandemic daily public transit needs. The goal of this project was to use Numpy and Pandas to clean and analyse the MTA subway transit data to come out a survey plan to help determine the best locations for new stations. I worked with with data from the MTA website between April 2021 and October 2021 to extract the busy level of each station and different time blocks for further analysis. After cleaning and analysing the data, I plot several bar plot to visualize and communicate my results using Seaborn. Finally, I came out a preliminary Survey plan for the client.

### Design

My goal is to find the busiest stations and the corresponding time blocks that worth sending surveyors to so that enough information can be collected. Following metrics are analysed and presented in this project:

1. Total Entries for each station.
2. Time blocks of a specific entries quantity.
3. Weekdays or weekends of a specific entries quantity.
4. Cold or Warm season of a specifc entries quantity.

### Data

I used the MTA data between April 2021 and October 2021, total seven months. I used the Entry for each station as the main analyses target.


### Algorithms

I mainly used below functions from Pandas and numpy to perform the data cleaning and data analyses (Please see the Analysis code file for detail):

1. Groupby
2. to_datetime
3. sort_values
4. dayofweek
5. drop
6. apply
7. append (array)


### Tools

1. Numpy and Pandas for data manipulation

2. Matplotlib and Seaborn for plotting


### communication

I plotted several bar plots using Seaborn to visualize the following metrics:

1. Top 10 stations of total entries.
2. Top 10 busiest time blocks.
3. Time blocks of the top 10 busiest stations.
4. Percentage of weekdays for the top 10 busiest stations.
5. Comparison between warm and cold season for the top 10 busiest stations.



