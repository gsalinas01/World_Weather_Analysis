# World_Weather_Analysis
## Overview
  * This project consists of developing code for a theoretical app called PlanMyTrip, which allows users to input temperature preferences and receive a customized vacation search and respective Itinerary. The project is made up of three technical analyses:
    * Retrieve Weather Data from 2000 cities around the world
    * Create a Customer Travel Destinations Map based on Temperature preferences
    * Create a Travel Itinerary Map based on 4 chosen cities

## Retrieving Weather Data
  * To retrieve Weather Data from 2000 cities, various tools were utilized such as:
    * Pandas, Numpy, CitiPy, and Google APIs
  * The following is the dataframe retrieved:
  * ![Screen Shot 2021-08-03 at 11 01 56 AM](https://user-images.githubusercontent.com/60943801/128048280-d1aab34e-c172-4361-8345-4f4c115092cd.png)

## Customer Travel Destinations Map 
  * In order to create a Travel Destinations Map, user input on Temperature Preferences was gathered into a dataframe to generate potential cities to travel to.
  * From this data, nearby hotels (5000 m radius) were also calculated
  * The resulting analysis consisted of generating destinations on a marker layer map with pop-up markers as such:
  * ![Screen Shot 2021-08-03 at 11 28 58 AM](https://user-images.githubusercontent.com/60943801/128052050-5c6f91fe-3533-44e0-9c62-dba127ea818b.png)

## Travel Itinerary Map
  * To create a Travel Itinerary Map, four cities were selected as travel destinations and directions were generated from each city to the next.
  * Google APIs were utilized to generate route as such:
  * ![WeatherPy_travel_map](https://user-images.githubusercontent.com/60943801/128052374-c751a9cc-f905-4cb5-85df-495347f14908.png)


