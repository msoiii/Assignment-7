# Assignment-7

**Introduction: **

With over 2 billion monthly active users, YouTube is one of the most popular and influential social media platforms centered around video content.  I was intrigued to know what genres that users around the world consume the most.  
Project Goal: 
This project aimed to collect and analyze data from a website about the ‘Top 300’ Youtube channels and create a bar graph to display the results between categorical data and frequency. I used Beautifulsoup API, numpy, matplotlib, and pandas to clean and transform my data. 
Exploring Popular Genres: Key Questions
The 2 questions I decided to answer were: 
What is the most popular Genre type according to the website chart?
 Which Genre had the greatest video output?


**Data Source: **

I do not own the data used. My data source originated from us.youtubers.me, a site that tracks Youtube channels and videos and ranks them in a list order according to certain categories such as most subscribers, most likes, or based on country of origin. 
A limitation on this data source is that although the website is refreshed daily, it may not incorporate the latest data points at the present moment.
I selected the Top 300 Youtube channels from the website (https://us.youtubers.me/global/all/top-300-youtube-channels). The different attributes that were shown on the page were: rank, Youtube channel, subscribers, video views, video count, category, and date when the channel started. 
I could not find licensing indicating that the website data was protected. I used this data, assuming it was allowed for public usage, to complete an educational assignment for my Intro To Human-Centered Data Science (I310D) course.   


**Data Dictionary **

Rank =  This is an integer data type that shows the rank of the Youtube channel based on the number of video views compared to the other channels on the list.
Channel_name = This is a string data type that displays the name of the Youtube channel
Subscriber_count = This is an integer data type that shows the number of subscribers, or followers,  a Youtube channel has.
Video_Views = An integer data type that displays the sum views of all videos a Youtube channel has gotten.
Video_Count = An integer data type that displays the total number of videos a Youtube channel has published.
Genre = A string data type that shows the specific category it is labeled as. 
Channel_Started = An integer data type that displays the year the Youtube channel was created.


**API Documentation: **

Here is a link to the Beautiful Soup API documentation: https://beautiful-soup-4.readthedocs.io/en/latest/ 
