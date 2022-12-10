# World_Weather_Analysis

## Overview
This analysis looks a different weather patterns in over 500 cities around the world. The purpose is to provide travelers with tools that will help them determine future travel destinations based on weather conditions.

## Weather Database
A set of 2,000 random coordinates was generated to then use OpenWeatherMap to make an API call and retrieve weather data for the nearest cities.

![city_data_df](https://user-images.githubusercontent.com/116690861/206868828-55a4dbe3-d8d3-4ff7-82ac-6852817b3fe2.png)

## Vacation Search
Using the information from the weather database, travelers can decide where they want to travel based on their weather's preference. The map below shows destinations with a max temperature between 70 and 95 degrees. 

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/116690861/206869087-23976ccb-bd9f-4039-8a19-d6c6fa351e4c.png)

## Vacation Itinerary
Using the Geoapify API a sample travel itinerary was created to show the route between four nearby cities. 

![WeatherPy_travel_map](https://user-images.githubusercontent.com/116690861/206869273-acc6c7ae-8096-4b25-b18d-03ca9980977f.png)

