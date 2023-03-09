# API Pythnon Challenge Requirements

## Part 1: WeatherPy:

* Create Plots to Showcase the Relationship Between Weather Variables and Latitude
  * Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code

   ![image](https://user-images.githubusercontent.com/113384120/224121082-f6d50e39-ee65-458d-8986-ddcc089528d8.png)

  * Create a scatter plot to showcase the relationship between Latitude vs. Temperature 
  
  ![image](https://user-images.githubusercontent.com/113384120/224121322-b0fbee75-01a3-4c2e-a8d5-865ee3ebe6a5.png)

  * Create a scatter plot to showcase the relationship between Latitude vs. Humidity 
  
  ![image](https://user-images.githubusercontent.com/113384120/224121424-d61956b0-e4ce-47cc-a731-c5f352ca8484.png)

  * Create a scatter plot to showcase the relationship between Latitude vs. Cloudiness 
  
  ![image](https://user-images.githubusercontent.com/113384120/224121483-a5036ecb-98e1-482d-ad20-8596aedbd17a.png)

  * Create a scatter plot to showcase the relationship between Latitude vs. Wind Speed 
  
  ![54c08f0a-dd60-4ea1-827a-3a3b320565b2](https://user-images.githubusercontent.com/113384120/224121703-72a9cbfc-6465-44de-b667-7f70e1653ad3.png)


* Compute Linear Regression for Each Relationship (40 points)
  * Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude (5 points)
  * Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude (5 points)
  * Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude (5 points)
  * Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude (5 points)
  * Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude (5 points)
  * Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude (5 points)
  * Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)
  * Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)

## Part 2: VacationPy:

* Create a map that displays a point for every city in the city_data_df DataFrame (5 points)
* Narrow down the city_data_df DataFrame to find your ideal weather condition (5 points)
* For each city in the hotel_df DataFrame, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates (10 points)
* Add the hotel name and the country as additional information in the hover message for each city in the map. (10 points)
