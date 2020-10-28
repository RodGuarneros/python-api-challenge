# Python Api Challenge
# Do you want to know the best cities and hotels to go fishing? This code answers your questions about it.

![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/markermap.png)

Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

First of all, please consider include your own api_keys for weather api (config.py) and google api (config2.py).

The visualizations are available in the folder called: "Images". 

## Create a series of scatter plots to showcase the following relationships, here some examples what you can find inside:

• Temperature (F) vs. Latitude

![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/City%20Latitude%20vs%20Temperature.png)

• Humidity (%) vs. Latitude

![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/City%20Latitude%20vs%20Humidity.png)

• Cloudiness (%) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/City%20Latitude%20vs%20Cloudiness.png)

• Wind Speed (mph) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/City%20Latitude%20vs%20Wind%20Speed.png)

Linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

• Northern Hemisphere - Temperature (F) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/NH%20LATvsMaxtempReg.png)

• Southern Hemisphere - Temperature (F) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/SH%20LATvsMaxtempReg.png)

• Northern Hemisphere - Humidity (%) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/NH%20LATvsHumidityReg.png)

• Southern Hemisphere - Humidity (%) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/SH%20LATvsHumidityReg.png)

• Northern Hemisphere - Cloudiness (%) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/NH%20LATvsCloudReg.png)

• Southern Hemisphere - Cloudiness (%) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/SH%20LATvsCloudinessReg.png)

• Northern Hemisphere - Wind Speed (mph) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/NH%20LATvsWindReg.png)

• Southern Hemisphere - Wind Speed (mph) vs. Latitude


![Alt Text](https://github.com/RodGuarneros/python-api-challenge/blob/main/starter_code/Images/SH%20LATvsWindReg.png)
