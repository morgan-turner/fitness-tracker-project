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

Data was inspected, organized, and cleaned in Microsoft Excel before being loaded into Tableau for visualization.

<h2>Analysis</h2>
For the purposes of this analysis, the question of searching for trends across the user base is extremely broad: this warrants more discussion of the stakeholder's goals and interests. However, for now, there are a number of interesting data points here. For example, in the daily data we can look at the date, total steps, total distance, distance over activity type, minutes of activity type, calories burned, minutes asleep, and minutes in bed. Some further questions I'll try to answer in regards to everyday use of the fitness tracker are: <br> <br>
1. Is there a correlation between overall activity (using step count as a proxy) and calories burned? <br>
2. Is there a correlation between overall activity (using step count as a proxy) and their sleep minutes?<br>
  2a. What percentage of users are logging <i>only</i> very active to fairly active minutes? Are these users tracking any sleep minutes? If not, this may indicate that these users are wearing their devices for workouts and then removing them the rest of the time.<br>
3. What chronotype are fitness tracker users? Are they more active in the morning, afternoon, or evening? This can be analyzed with users' hourly step count. <br>
4. Do users prefer rigorous workouts or more lowkey forms of exercise like walking? To answer this question we'll look at activity type over minutes and determine which activity group (very active, fairly active, lightly active) has the highest representation in the dataset. We'll likely exclude the sedentary activity type as this is the time when users are likely at rest or sleeping. <br>

<h2>Discussion</h2>

Initial analysis of user activity shows that users are primarily sedentary when wearing fitness devices. This observation makes logical sense, since sleep takes up one third of a 24-hour period and users are likely wearing their devices all the time. Many users may additionally have sedentary office or administrative jobs, which could account for the remainder of inactive time. 

<img width="700" alt="user activity summary" src="https://user-images.githubusercontent.com/92185928/172508444-26322cb1-1b9f-46a5-8b96-c902f1db5bdf.png">

Eliminating sedentary time from the analysis gives a better picture of what type of activity users prefer when they choose to work out: light activity, moderate activity, or very active (rigorous) activity. As demonstrated in the chart below, users clearly have a preference for light activity like walking, yoga, or pilates. These exercises are almost universally beneficial, low-impact, and easy to incorporate into one's daily routine. These are good options for people seeking to build a more active lifestyle, especially for those exploring how to live more healthfully for the first time. Interestingly, more rigorous workouts like running, kickboxing, or HIIT are the next most popular workout type and make up nearly 10% of user activity outside of sedentary behavior. These users want to work up a sweat! 

<img width="750" alt="activity" src="https://user-images.githubusercontent.com/92185928/172512463-b84308f8-1a83-4e23-8158-83a5f7c68069.png">




<h2>Recommendations</h2>

[...]
