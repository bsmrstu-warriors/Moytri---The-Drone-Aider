Moytri: The Drone Aider
=======================


Necessary Tools:

-Visual Studio
- DirectX Redist
- Microsoft .NET 4.0
- 

Description:

Often we heard small drone has crashed due to rough weather or by knocking with other objects. Sometimes these crashes can be costly because the damage occurred to the drone might be too extensive. Again drone can accidently fly in the restricted zone because the drone operator does not have any idea of these restricted air space. So to solve this problem we have made an application which will help the drone operator. We are calling it Moytri: The Drone Aider.
Our application is based on windows form application. We used GMap. Net library, Google maps service server side programming and Mavlink protocol for getting sensor data from the drone. For solving the weather problem we used open source weather API. By using the API we can know the current temperature, wind speed and direction, visibility, dew point of the area where the drone operator is. We have made a system, when the wind speed is too high for the drone our application will automatically alert the operator.
We have made our application in a way that it can take the GPS coordinate as input parameter. That’s why it can be integrated into all the drone operating system. In our system we have drawn a circle of five mile radius from the operator location. And we have represented no fly zone/ restricted area in the map by drawing red rectangle around it. Also if there is any restricted area within five mile radius of the drone, the operator will automatically be notified. By that there will be no chance of trespassing in the no fly zone.
But the uniqueness of our app is we can predict the future position of the drone using linear regression. We can prevent accident by providing minimum safety altitude also warn about no fly zone area. We can provide accurate data at offline using our algorithm. 250KPH wind speed is a normal value to computer but in human life it is a cyclone. Our machine is able to understand that danger. Also it can predict the weather by using the weather parameter also using archive data using Naive Bayes Algorithm.
Drone operator can visually inspect the sky for avoiding crash with other objects but the line of sight cannot go too much far. So to solve this problem we used Google maps satellite image. Which gives us zoom capability. We have marked the vegetation area with green rectangle and the river is easily understandable from the satellite image. Also we marked the communication tower with Altitude measurement. So drone operator can know which tower is how much high.
Conventional drone controller does not give these kind of features.


Data we used from: 
- nationalmap.gov
- weather.gov
- noaa.gov/weather
- Google Maps
- Mission Planner
