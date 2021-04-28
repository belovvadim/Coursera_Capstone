# Capstone Project Description  

This Applied Data Science Capstone project is part of the IBM Data Science Professional Certificate on Coursera

##  1. Introduction and description of the problem  

Finding the right surrounding area to live, that fits your personality and preferences, can often feel like a challenge. It is especially difficult to choose among various locations when moving to a new city that you know little or nothing about. The decision should take into account a variety of factors (such as affordability, available infrastructure, transport, etc.), as well as evaluate possible risks. With so many different options to consider, how can one better weight all the possibilities and make the right choice? 

For this project, I would like to analyze the particular city of interest, using the methods of data science to better understand and compare different neighborhoods. I have chosen to consider the city of Chicago, which is completely unknown to me, so that way I will also be learning a lot in the process (which is the part of fun). I will try to evaluate the city's various regions based on the following three criteria:

1. Which areas are most dangerous / safest?
2. Where the cost of living is more affordable and where it is high?
3. What are the differences and similarities between neighborhoods in terms of local infrastructure (e.g., like food or entertainment venues)?

To answer each question, I am going to leverage open data sources to draw few general conclusions on the relative merits of different areas, that will help to make a better informed decision. Thus, the project is mostly exploratory in nature and, hopefully, can be useful to someone new to Chicago (like me), who plans to visit or even stay there in the future. Finding patterns in the venues among different neighborhoods, in general, can also provide valuable insights about locations to open new business.

## 2. Data  

In accord with the above outline of the scope of planned analysis, I will combine various types of data, acquired from multiple available resources. 

1. First I will gather geographic data on the Chicago's administrative division and area boundaries through Chicago Data Portal. Information on local neighborhoods and their coordinates can be obtained via webscraping (e.g., Wikipedia) and geocoding API's (e.g., Google or OpenStreetMap), respectively. From the cleaned and processed data I will create an interactive map that will give me a good overview of the city's complicated geography.

2. Chicago Data Portal also provides a very detailed and (almost) up-to-date crime statistics, starting from 2001, gathered by Chicago Police Department. This has to be combined with the population data (also found there), in order to evaluate and compare the crime rate for different areas.

3. The information on rental / house prices is available on multiple real estate resources (either through specialized API, or using the webpage scraping for relevant numbers).

4. Finally, I will the Foursquare API location data to obtain information on various categories of local venues for each neighborhood (using the collected coordinates).