# World_Weather_Analysis

## Overview
Traveling is a big part of many peoples lives. As we all know, weather can play a big role in whether your vacation is a success or not. The purpose of this analysis is to collect, analyze, and visualize weather data across cities worldwide in order to provide a tool to all travlers alike to make destination decisions based on weather conditions.

## Resources Utilized for Analysis
- CVS Files: Weather_Database.csv, WeatherPy_vacation.csv
- Jupyter Notebook Files:: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb
- Python: Python v3.7.6, Dependencies: Pandas, Matplotlib, CitiPy, SciPy, Python Requests, APIs, JSON Traversals

## Weather Database
We first generated a random set of 2,000 latitude and longitude coordinates. Then, an API call was made on the current weather data for the nearest corresponding cities to those coordinates. 

We retrieved a handful of data points from the API call:
  - Latitude and Longitude
  - Maximum Temperature
  - Perecent Humidity
  - Percent Cloudiness
  - Wind Speed
  - Current Weather Description

## Vacation Search
Using the input from a specific traveler's weather preferences, the traveler is able to look up many potential travel destinations along with hotels in those areas that best suites their needs. The map below shows an example of potential destinations using pop-up markers on a marker layer map.
![VacationSearch](https://github.com/RyleeJensen/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Vacation Itinerary
To take the analysis a step further, we used the Google Directions API in order to create an itinerary of a potential travel route between cities. Below is an example of a route between four cities.
![VacationItinerary](https://github.com/RyleeJensen/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
