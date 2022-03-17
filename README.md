# Variation of temperature around the world: Project Overview

This project have as main objective understand how mean temperature per year is different in different places of earth. 

-I made a heat map to undertand how the temperature is distribute around the world.

-I calculated the variation of temperature during the year in the main cities around th globe

-I selected the cities with most and less variation and made a comparison of that variation during the las years.


 # Code and Resources Used
 
Python Version: 3.10

**Packages**: pandas, numpy, matplotlib, seaborn, geopandas, pycountry-convert, geopy


# Explore and clean data

The data was taken from Kaggle: Daily Temperature of Major Cities: https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities

I made the following changes to the data frame:

-Delete the State column

-Convert the Avg Temperature column to Celsius

-Delete all entries containing null values 

I used the thermal variation and low average temperatures as criteria to do data cleaning.

temperature distribution after doing data cleaning 
![temp1](https://user-images.githubusercontent.com/74560416/158899587-6aa8e6d3-3af3-43ca-b451-efbbab31e9ba.png)


# Processing data

I created a second table and save it as .csv with the columns: city, country, average annual temperature, annual thermal variation (largest difference between highest and lowest annual temperature).

I arranged the database in ascending order from highest average temperature to lowest average temperature 

Next, I made a heat map of the cities with the greatest thermal variation throughout the last year registered in the database (if the map cannot be made by cities, do it by country)

![temp2](https://user-images.githubusercontent.com/74560416/158900117-9e520957-df38-419c-ba4a-3c741f2f21cc.png)


I established the five cities with the highest annual thermal variation, and the lowest variation, and made a graph for each city showing how this variation has changed over the period of time covered by the database. 

![temp3](https://user-images.githubusercontent.com/74560416/158900130-8df245c3-d479-436c-8364-148ee5df4471.png)

# Results

After analyzing the data i found that countries close to equator are hotter and have a more stable temperature and countries close to the poles are cold and have a high of temperature variation, as expected. 

But in both kind of places, hot and cold, we find that the temperature variation is not changing, in general, evnthough its not stable if we look at specific cases. But at the same time i find that in the year 2020, the temperature variation is lower, this was the same year that the emision of CO2 were lower too.


You can see the code in: https://github.com/Chelo-ad/Temperature_around_the_World/blob/main/Temperature(1).ipynb
