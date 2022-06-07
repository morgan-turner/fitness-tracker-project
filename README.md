# Bellabeat Case Study: How Can a Wellness Technology Company Play It Smart?

<h2>Introduction</h2>
<img width="223" alt="bellabeat_logo" src="https://user-images.githubusercontent.com/92185928/170800905-eaa108af-7a5f-45e6-ac5f-f9fc19b29d54.png">
Bellabeat is a fictional manufacturer of health-focused technology products for women. Founded in 2013 and now a successful small company, Bellabeat wants to expand further into the global smart device market. The company currently offers several smart device products including a wellness tracker, a smartwatch, and smart water bottle, and an app to connect to these smart products and manage user data. Bellabeat offers a subscription-based membership for users to access fully personalized guidance on nutrition, activity, sleep, and mindfulness based on their lifestyle and goals.

<h3>Stakeholder Goals</h3>
In order to better inform Bellabeat's marketing strategy, the company's cofounder and Chief Creative Officer would like to understand how consumers use smart devices across the market and find out how that may translate to the way Bellabeat consumers use their devices. They want to understand the following:<br><br>
<b>
1. What are some trends in smart device usage?<br>
2. How could these trends apply to Bellabeat customers?<br>
3. How could these trends help influence Bellabeat marketing strategy?</b>
  
<h2>Data</h2>
The dataset is made up of external data not provided by Bellabeat. It is a series of observations of 30 individual fitness device users from which the Bellabeat marketing team hopes to extrapolate information about its own consumers. <br><br>

To approximate this data, this case study is an analysis of a public datset of 30 individal Fitbit users' tracking behaviors as recorded by their wearable fitness technology devices over a period of two months. This data provides users' calories burned, activity intensity, step count, and sleep behavior, aggregated over days, hours and minutes. This dataset can be found [here](https://www.kaggle.com/datasets/arashnic/fitbit).

To better focus this analysis we will look for trends in user data across fitness level, sleep length, and step count aggregated daily. If further analysis is needed, we may look for activity trends throughout the day, such as whether users are more active in the morning or evening. 

<h3>Limitations</h3>
30 users is the lower threshold for the sample size of a study whose results have statistical significance. Ideally, the data team would find and study a dataset with a higher number of users so as to avoid sampling bias.  <br><br>

Additionally, some of the provided data, such as the weight log files, are unusable for analysis due to user inconsistency. Out of 30 users, only 2 were consistent in manually adding their daily weight to the app throughout the 30 day sampling period, so unfortunately this analysis will be unable to provide insights on how fitness tracker wearers may be using their devices for weight loss. 

<h3>Data Preparation</h3>
For the most straightforward analysis, data was arranged according to granularity. Daily data (activity level, daily steps, sleep hours) was compiled together and hourly data was analyzed separately to assess chronotype trends across users. This analysis will focus on overall user habits over days and hours, rather than the more granular minute-by-minute observations recorded by the fitness device. <br><br>

Data was inspected, organized, and cleaned in Microsoft Excel before being loaded into SQL to produce new joined tables for visualization in Tableau.  

<h2>Analysis</h2>
For the purposes of this analysis, the question of searching for trends across the user base is extremely broad: this warrants more discussion of the stakeholder's goals and interests. However, for now, there are a number of interesting data points here. For example, in the daily data we can look at the date, total steps, total distance, distance over activity type, minutes of activity type, calories burned, minutes asleep, and minutes in bed. Some further questions I'll try to answer in regards to everyday use of the fitness tracker are: <br> <br>
1. Is there a correlation between overall activity (using step count as a proxy) and calories burned? <br>
2. Is there a correlation between overall activity (using step count as a proxy) and their sleep minutes?<br>
  2a. What percentage of users are logging <i>only</i> very active to fairly active minutes? Are these users tracking any sleep minutes? If not, this may indicate that these users are wearing their devices for workouts and then removing them the rest of the time.<br>
3. What chronotype are fitness tracker users? Are they more active in the morning, afternoon, or evening? This can be analyzed with users' activity hourly step count. <br>
4. Do users prefer rigorous workouts or more lowkey forms of exercise like walking? To answer this question we'll look at activity type over minutes. <br>

<h2>Discussion</h2>

[...]

<h2>Recommendations</h2>

[...]
