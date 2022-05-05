# World Weather Analysis

## Overview

### This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip. There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.

## Weather Database
  - This folder uses Open Weather Map API to pull weather information on over 694 different cities around the world. That information consists of:
    
    --Maximum Temperature
    --Cloudiness
    --Wind Speed
    --Humidity
    --Current Weather Description

-These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination.

## Vacation Search
  - This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each locatios for 721. For example, the image below shows the locations of all the places in the database that have an daily maximum temperature between 4 5and 65 degrees farinheit.
![Vacation_Search](https://user-images.githubusercontent.com/99519095/166861460-e38a20b3-42fc-417a-847a-9b9c430fadaf.png)

## Vacation Itinerary
  - This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4 stop itinerary in Northern California that features Ukiah, Carson City, Laguna, and Half Moon Bay.
  - ![Vacation_travel_Markers](https://user-images.githubusercontent.com/99519095/166861603-1db56931-9284-4a41-8762-ed86ec6cd4a7.png)
