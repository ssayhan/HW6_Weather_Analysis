## WORLD WEATHER ANALYSIS

## PROJECT OVERVIEW

In this project, we will help jack who loves the PlanMyTrip app. Also Beta testers love it too and they have couple recommended to take app to next level.

We will put input statement and beta tester can filter the data for their weather preferences, which will be use to identify potential travel destinations and nearby hotels. And then we will use the Google Maps Directions API to create a travel route between the four cities as well as marker layer map.
Resources
•	Software
o	Jupyter Notebook
•	Enviroment
o	Python 3.7
•	Dependencies
o	Pandas Library
o	Numpy Library
o	CitiPy Module
o	Python Requests
•	APIs
o	Open Weather APIs 
o	Google Maps API 
o	Google Directions API 


### 1.	Weather Database

We used NumPy random module to retrieve 2000 random coordinates and CitiPy module to define the closest city names based on coordinates. After that we used Open Weather API to request json data from website. In the end we transform the data into the Pandas data frame an saved as csv.
 
<img width="807" alt="Database" src="https://user-images.githubusercontent.com/77603561/167061224-ecbabe88-8cf0-4ec4-8e0c-a2f2ddb2f1b1.png">

### 2- Vacation Search

We used loc method to on Weather data to filter it and next we retrieved to get hotel names via Google Maps API. we plotted the map with pop-up messages that includes hotel name, city and country with Jupyter gmaps module.

<img width="817" alt="Vacation Search" src="https://user-images.githubusercontent.com/77603561/167061292-61b2294c-44a6-4939-a3cd-e8607f8f3390.png">


### 3-	Vacation Itinery

We selected 4 hotels destinations to extract coordinates with yo_numpy() function and we connected them with Google Directions API via selected travelling mode.


<img width="785" alt="Screen Shot 2022-04-28 at 1 41 42 AM (2)" src="https://user-images.githubusercontent.com/77603561/167061301-db13a625-6d11-4949-9f03-85cb30c94ebc.png">
<img width="805" alt="Mark the cities" src="https://user-images.githubusercontent.com/77603561/167061313-1b0a0ddb-d7b0-44d1-924c-4ea399b2597d.png">



