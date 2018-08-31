## Weather-Py
What is the weather like as we approach the equator? 

I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. I utilized a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

I built a series of scatter plots to showcase the following relationships:


Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude



# What I used: 
    - Python requests
    - JSON Traversals
    - Pandas
    - Matplotlib
    - Numpy 
    - Jupyter Notebook
    - Open Weather Map API Key and documentation

# What I did:    
    - I performed API calls to gather weather data to create a Data Frame with the following infomation:
        - Cities
        - Latitude
        - Temperature
        - Humidity 
        - Cloudiness
        - Wind Speed
    - With this data, I created multiple scatter plots of showing the correlation between latitude and each variable.    

# Observations from my scatter plots:
1. Cities located closer to the equator generally have higher temperatures. This was expected. 
2. Humidity seems to be highest between 20 and 40 degrees latitude (or -20 and -40). This is right around the tropics of capricorn and tropics of cancer. Right near the euqator and near the poles has less humidity. 
3. No there is no correlation between latitude and cloudiness. 
