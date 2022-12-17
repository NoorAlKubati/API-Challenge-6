# API-Challenge-6

## Deliverable 1:
I Created a folder called Weather_Database to save all the files related with this deliverable. Then I saved the Weather_Database_starter_code.ipynb starter code to the Weather_Database folder and rename it as Weather_Database.ipynb. I used the np.random.uniform function to generate a new set of 2,000 random latitudes and 2,000 longitudes. I also used the citipy module to get the nearest city for each latitude and longitude combination. After that, I mported OpenWeatherMap's API key and assembled the API call URL as a string variable. For confidiality, I added a file calld .gitignore to save my API key to avoid publishing my API key on your GitHub repository. Retrieve the Latitude and longitude, Maximum temperature, Percent humidity, Percent cloudiness, Wind speed, and Weather description. Last, I added the weather data to a new DataFrame.

## Deliverable 2:
I started by create a folder called Vacation_Search to save all the files related with this deliverable. Then I download the Vacation_Search_starter_code.ipynb Jupyter notebook,save it into your Vacation_Search folder, and rename it as Vacation_Search.ipynb. In the Vacation_Search.ipynb file, I ensured that the dependencies and the Geoapify API key is imported correctly. From the Weather_Database folder you created in the "Deliverable 1," import the WeatherPy_Database.csv file as a Pandas DataFrame named city_data_df. I wrote two input statements that prompt the user to enter their minimum and maximum temperature criteria for their vacation. I also create a new Pandas DataFrame by using the loc Pandas method to filter the city_data_df DataFrame for temperature criteria collected. Name the DataFrame as preferred_cities_df. After that, I create a new Pandas DataFrame named clean_travel_cities by using the Pandas dropna function on the preferred_cities_df to drop any empty rows.

























