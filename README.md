# python-api-challenge

The first part of this project looks at the correlation between the latitude of a city (i.e., how close it is to the equator) with other meteorological phenomena. 

First, we randomly generated a list of over 600 cities and found the current weather for all, including temperature, cloudiness, humidity, and latitude / longitude points.

After cleaning the dataset, we plotted the following variables on separate graphs: latitude vs. temperature, latitude vs. humidity, latitude vs. cloudiness, and latitude vs. wind speed. We then separated the dataset out by northern and southern hemisphere and looked at the same plots.

The second part of the project created two heatmaps which showed the humidity at each of the randomly generated cities. We then filtered the data to only fit certain criteria (e.g., temperature between 75 and 90 degrees F, wind speed less than 10mph, and cloudiness less than 15%). Only 24 cities matched these criteria, so we searched for hotels in each city and plotted the name of the city, the country, and the name of the hotel on top of the previously-generated heatmap for a final visualization.
