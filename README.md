## **Objective**

The objective of this project is to create a prefect place detection tool which'll find the best neighbourhood or place to open a start up or restaurant using Foursquare API. In this project we'll take Italian Restaurant as an example.That is we'll find the best place or neighborhood to open an Italian restaurant in Toronto(A city in Canada) using Foursquere location data.

### **Target Audiance**

* Business personnel who wants to invest or open a start up company or restaurant.
* Bachelors who want to stay in a good city where they can get each facilities what they want like GYM,Playground,Parlour,Movie theatre etc.
* The freelancer who loves to have their own small company or restaurant as a side business.
* Marketing companies who want to release a new product on a best place.
* Researchers who want to create a camp for Survey.
* Torrists who wants to eat italian food.


## **Data Description**
For this project we need these following data:
1. ***Toronto City data that contains Borough, Neighborhoods along with there latitudes and longitudes***
* **Data Source:** https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M
* **Description:** This Wikipedia page contain all the information we need to explore and cluster the neighborhoods in Toronto. We will be required to scrape the Wikipedia page and wrangle the data, clean it, and then read it into a pandas dataframe so that it is in a structured format like the Toronto dataset.
2. ***Geographical Location data using Geocoder Package***
* **Data Source:** https://cocl.us/Geospatial_data
* **Description:** The second source of data provided us with the Geographical coordinates of the neighbourhoods with the respective Postal Codes.
3. ***Venue Data using Foursquare API***
* **Data Source:** https://foursquare.com/developers/apps
* **Description:** From Foursquare API we can get the name,category,latitude,longitude for each venue.

## **TechStack/framework used**
- Machine Learning
- Web Scraping
- Foursquare API
- Geocoder
- Beautiful Soup
- Folium

 In this capstone project we are going to answer of these following major steps:

* **Assignment-1:** Scrape the data from the wikipedia page of Toronto.

* **Assignment-2:**  Get the geographical coordinates of the neighborhoods using the Geocoder package.

* **Assignment-3:** Explore and cluster the neighborhoods in Toronto.
