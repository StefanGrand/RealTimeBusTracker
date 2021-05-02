# RealTimeBusTracker

##Purpose
There is a bus operating between the MIT campus and Harvard. The local bus service provider gives software developers the chance to get real time data about the operating buses.
         
##Background
First you need to establish an API to mapbox (map provider (open source until a specific usage limit)). There are several other providers for these services (e.g. google maps). The functions are established in an asynchronous way to ensure a good user experience. The function #getBusLocation fetches the data, converts it to a json data file. #run initiates all functions with help of a timer (Set to 15sec-> all 15 seconds the bus locations are displayed). Function #addMarkers filters the longitude and latitude of each bus and set a marker on the map (depending on the direction of the bus in blue or red).
               
Goal: Showing the locations of each bus in real time on the map of Boston.

##Installation
The code was tested on Google Chrome. Once loaded, the animation starts with a mouse click in the window. Clicking on the PacMan he becomes faster.

##Roadmap
For the exercise, it was the goal to address asynchronic code and to set up API's to external sources. 

##License Information
This work was done as part of MIT xPRO Professional Certificate in Coding. The code above comes with the following license:

MIT License
