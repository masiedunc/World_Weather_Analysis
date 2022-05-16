# World Weather Analysis
## Overview of Project & Retrieving Weather Data
Working with a travel agency, Open Weather and Google Maps APIs were utilized to parse data to analyze the best time of year for travel. The application that was being developed will allow its users to find the best places, dates, and weather for traveling based on their own preferences for an ideal temperature. The approach for gathering data was to generate a dataframe of cities using latitudes and longitudes that were randomly created. In Image 1, a preview of the dataframe is shown and includes the city, country, coordinates, max temperature, percent humidity, percent cloudiness, wind speed, and current weather description.
![Weather_Database](https://user-images.githubusercontent.com/102122063/168509368-4bfd1b11-c1de-4b6b-930e-895d6980fbe3.png)

**Image 1:** *Weather Database from May 15, 2022.*

## Creating a Customer Travel Destinations Map
With the help of beta testers (users), we were able to test an application for utilizing user preference responses to help create a Customer Travel Destinations Map. The users were asked to input their ideal minimum and maximum temperatures for vacation. Based on user inputs, a new DataFrame was created to only include cities that met the input criteria. The Google Maps API allowed us to then create a map of the hotel locations that included markers and pop-up boxes with information including, city, country, hotel name, and current weather. Image 2, shows all of the hotels that fell within the range of a minimum temperature of 75 degrees and a maximum temperature of 90 degrees.
![Vacation_Search](https://user-images.githubusercontent.com/102122063/168509937-787a2cd1-d8bc-4aa3-87bc-e91c35f1ea67.png)

**Image 2:** *Vacation/Hotel search from May 15, 2022 based on user's input responses for max/min temperature.*

## Creating a Travel Itinerary Map
After narrowing down the search for vacation locations, four cities were chosen within one country to create a vacation itinerary. However, in this case, there were four cities relatively close in both Malaysia and Thailand, and it was decided that it'd be amazing to be able to visit two countries instead of one! Utilizing NumPy, I was able to create an index of coordinates for each stop to create a travel guide with driving directions between the four cities. Gmaps were used to add the markers and the directions layer. You can find the driving directions below in Image 3.
![WeatherPy_travel_map png](https://user-images.githubusercontent.com/102122063/168511130-dd10beb6-6763-4e18-aa17-f6fe4d84c01a.png)

**Image 3:** *Vacation Intinerary map with driving directions bewtween four stops in Malaysia, search from May 15, 2022*


![Vacation_Itinerary_df](https://user-images.githubusercontent.com/102122063/168510045-ea947784-27ce-46d1-a18b-4322c11bbf88.png)

**Image 4:** *Vacation Itinerary DataFrame search of four vacation stops in Malaysia, search from May 15, 2022.*

