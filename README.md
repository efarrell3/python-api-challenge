# python-api-challenge

General Observations:
  Basic trends seen in the first four plots, titled: Latitude v. Temperature Plot, Latitude vs. Humidity Plot, Latitude vs. Cloudiness Plot, and Latitude vs. Wind Speed Plot, include:
   
   - For the Temperature comparison plot we can see that max temperature increases as latitude moves closer to the equator and peaks between -20 and 20 degrees latitude.  This is an expected outcome bevause the latitude extremes are the poles of our planet, which means those areas are farther from the sun.
   
   - For the humidity plot, there is no real trend seen in the cities that are plotted against latitude.  This can be expected because humidity changes based on a number of factors, one of them being the distance from a body of water.  Since we didn't use distance from the ocean as a factor when creating our plots, we aren't seeing a trend.  The same can be said for cloudiness and wind speed.  We aren't seeing trends in either of those plots either.
    
The next plots created are comparing the same factors latitude vs. max temp, humidity, clodiness, and wind speed; but we split the northern and southern hemispheres (i.e. the positive and negative values from the first four plots respectively).  I will analyze linear regression lines for each of the factors and compare them between hemispheres:
  - For the temperature plots:
    - The northern hemisphere linear regression line fits the data better then the southern hemisphere line, based on their   respective r-squared values.  Based on these models, I would confirm that northern hemisphere cities are warmer closer to the equator and colder farther from it in a more linear trend than southern hemisphere cities. 
    - The next 6 r-squared values reveal that there is no trend between cloudiness, humidity, and wind speed with regard to latitude.  Even when the comparison cities are divided by hemisphere. 
   

