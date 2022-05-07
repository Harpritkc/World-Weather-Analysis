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
  - This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4 stop itinerary in France Vertou, Soyaux, Manosque, and Concarneau

  - City_ID	City	Country	Max Temp	Current Description	Lat	Lng	Hotel Name
0	467	Vertou	FR	46.38	clear sky	47.1687	-1.4693	Hotel La Louée
1	512	Soyaux	FR	54.68	clear sky	45.6500	0.2000	Mercure Angoulême - Hôtel de France
2	613	Manosque	FR	50.23	overcast clouds	43.8288	5.7869	Hôtel Restaurant Campanile Manosque
3	638	Concarneau	FR	46.81	overcast clouds	47.8750	-3.9225	Brit Hotel de L' Océan
 ![Vacation_Itinerary withRoute](https://user-images.githubusercontent.com/99519095/167238899-6b754462-07bb-4cfd-a7eb-b92bd21b7ff1.png)
![Vacation_travel_Markers](https://user-images.githubusercontent.com/99519095/167238901-614ec41b-55c4-4e3e-811b-20fb240ffb93.png)
![Vaction ItinerayLocatiom](https://user-images.githubusercontent.com/99519095/167238903-a3428b64-9fff-40f5-b610-a231cf20766b.png)

