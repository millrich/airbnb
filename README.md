# Project overview
A data science project that uses AirBnB public data for San Francisco to answer the question 'What makes people choose your AirBnB home?'

# Installation
1. Python version: 3.6.5 was used for this project
2. Libraries used: numpy, pandas, seaborn, datetime, Counter, sklearn, matplotlib, warnings
3. Jupyter Notebook is required

# Motivations
Explore and analyze the AirBnB public data for San Francisco on topics of Pricing, Occupancy and Review Ratings. Answer the following questons:
1. What are the most important factors that impact a listing's price?
2. What are the most important factors that impact a listing's occupancy rate?
3. What are the most important factors that impact a listing's review ratings?
4. What are the amenities AirBnB guests care most?

# Files
1. airbnb_sf.ipynb: The Jupyter Notebook file that describes the process of data anlysis. It contains the steps of data collection, cleaning, tranformation, as well as data modeling. 

2. utility.py: functions used by the Jupyter Notebook file 'airbnb_sf.ipynb'.

3. listings.csv.zip: The listings data set provides detailed feature information of each listing in San Francisco (as of 8/6/2018). There are 96 features associated with each listing such as property type, room type, number of bed rooms, amenities, review ratings, etc. Need to unzip it to CSV file.

4. calendar.csv.zip: The calendar data set provides availability and price information for the total 6632 active listings (as of 8/6/2018) in San Francisco for the next 12 months. Need to unzip it to CSV file.

# Blog
1. A blog was written based on this project. The blog's link:
https://medium.com/@wei.wade.wu/what-makes-people-choose-your-airbnb-home-a9d83722a712

# Summary of the results of the analysis
1. A listing’s price is mainly determined by its “hard” property features such as number of available rooms. And, a host may improve the listing’s price tag by enhancing “soft” property features like summary details
2. Number of reviews is one of the most important factors influencing a listing’s occupancy rate and review scores. A host should do all means to get as many reviews as possible in order to attract more guests.
3. WiFi and Essentials are must-have amenities that impact a listing’s occupancy rate and review rating.
