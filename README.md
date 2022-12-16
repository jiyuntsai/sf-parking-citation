# sf-parking-citations

Written by Jiyun Tsai for Advanced Coding Final Project at UC Berkeley Journalism School <br/>
November 5th, 2022

**ALL .csv files can be found [here](https://drive.google.com/drive/folders/1SJ0jPphZWaPy7h72a2X3uj4rI_nGH8hH?usp=share_link)**

## Description

Using [SFMTA - Parking Citations](https://data.sfgov.org/Transportation/SFMTA-Parking-Citations/ab4h-6ztd) from DataSF as the main dataset for analysis. The dataset is provided by San Francisco Municipal Transportation Agency (SFMTA) that contains each parking ticket issued since January, 1st, 2008 to present. The data includes the following information: citation number, issued date and time, violation description, citation location, vehicle plate, fine amount, and geolocation point.

Questions:
1. What type of violation gets the most ticket? Which neighborhood and when.
2. How does citations given by SFMTA looks like each year?
3. Where is the citation hotspot through time?
4. What was the citation situation like during pandemic? and pre-pandemic?
5. What type of violation gets the highest amount of fine?

Limitation and problems yet to solve:
1. The dataset has not provide more details of each violation abbreviation means and would need to call SFMTA for explanation.
2. How to aggregate neighborhood data into this dataframe.
3. Find the relations between citation hotspots and the factors.


*From initial analysis, most parking tickets are giving to **street cleaning** so if possible, I'd like to join [Street Sweeping Schedule](https://data.sfgov.org/City-Infrastructure/Street-Sweeping-Schedule/yhqp-riqs) dataset from DataSF to see if there's correlations between street sweeping schedule and ticket fines in certain area.
