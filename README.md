# Washington State Library Finder
**Contributors:** Alex Kirchmeier, Bjorn Soriano, Laura Kirk, Minjie Kim
## Project Description
For our final project in Geography 495: Web GIS, we have built an application that sorts data by distance to allow our users to identify nearby libraries to their location at the University of Washington and filter out relevant libraries based on category. We have also included a web map that includes the locations of all the libraries within the state of Washington. The base map that we created for our application has a light blue-gray monochrome theme that highlights the streets in black. We then included all the libraries in Washington in point format as a layer on top of the base map. Each library has an icon that distinguishes the main purpose of each library, categorized as academic, government, public, and special libraries. If you hover over each library, then it will display a popup of the library containing information such as its phone contact number, their website, long/lat location, city, county, and any other relevant information that helps our intended audience better choose the library for their needs. There is a search bar in the upper left hand corner of the map that allows users to type in their address and discover the library that is closest to them. Once a user types in and selects their address the map will zoom to their address and show the highlighted library that is closest to them with the information on that library.  

## Project Goals 
Libraries are very resourceful locations for students whether it is used as a tool for the research process, entertainment use (finding the next good book or renting a movie), or just as a quiet study space. However, we feel that libraries are often overlooked for research purposes these days due to the accessibility of resources online. By creating a convenient tool that helps users find nearby libraries in Washington state that correspond with their needs, we hope that they will be able to take full advantage of these wonderful resources, including the very helpful and knowledgeable librarians that work there! 

## Application Url: 
https://soriabjo.github.io/geog495_libraryfinder/index.html

## Screen Shots: 
1. This is what the application looks like when the user first loads it
<img src="/img/start.JPG" alt="start of application" width=800>
2. When you press on one of the buttons on the right side of the map, you can filter out that category shown on the map
<img src="/img/filter.JPG" alt="filter out category" width=800>
3. When you search a location, the maps moves and zooms on to that location
<img src="/img/location.JPG" alt="zoom into searched location" width=800>
4. When you click on an individual library marker, this is what the information panel pop-up looks like and the information that is shown, if there is data for it
<img src="/img/information.JPG" alt="library information pop-up" width=800>

## Main Functions:
The main function of our application is the sort by distance function of the web page. We designed the web page with a map on the right hand side showing the many different libraries in the state of washington. On the left hand side there is a panel that displays a list of all these libraries. The sort by distance function is implemented by the search bar that is located in the top left corner of the map. The user is able to enter the address of their current location in the search bar. The list of libraries on the left hand side will then reorder with the top library on the list being the one that is closest to the user's current location. 


## Data Sources:
We have settled on using data provided by Washington Geoservices and accessed through the [Washington Geospatial Open Data Portal](https://geo.wa.gov/datasets/f62ef46873bd4a80a31e3e88eafa43eb_0/explore?location=47.311825%2C-120.841168%2C7.40). This dataset provides coordinates for each library, as well as identifying information and key descriptors.

## Applied Libraries: 
The applied libraries that we used for the purposes of this project are Mapbox GL’s Javascript and CSS libraries. We also used the Mapbox Geocoder plugin and Turf.js, which allowed us to be able to calculate the distance between the user and the various libraries. To host our application on a website, we use GitHub Pages.

## Acknowledgments: 
We would like to give thanks to our professor, Dr. Bo Zhao, and our teaching assistant, Steven Bao, for teaching us the necessary tools and concepts throughout the quarter in order for us to complete this project successfully.

## Other Info: 
In order to complete this project, we followed various tutorials from Mapbox, [Build a store locator using Mapbox GL JS](https://docs.mapbox.com/help/tutorials/building-a-store-locator/) and [Sort stores by distance](https://docs.mapbox.com/help/tutorials/geocode-and-sort-stores/). 
 
### Icons
The icons used for our markers in our project are all from flaticon.com.

<img src="/img/academic.png" alt="mortarboard" width=100>

This [Graduation cap icons created by Iconiyo - Flaticon](https://www.flaticon.com/free-icons/graduation-cap) is used to signify academic libraries in the application.

<img src="/img/government.png" alt="Government building" width=100>

This [Government icons created by Vector Stall - Flaticon](https://www.flaticon.com/free-icons/government) is used to signify government libraries in the application.

<img src="/img/public.png" alt="person" width=100>

This [User icons created by Freepik - Flaticon](https://www.flaticon.com/free-icons/user) is used to signify public libraries in the application.

<img src="/img/special.png" alt="lightbulb" width=100>

This [Bulb icons created by Creative Stall Premium - Flaticon](https://www.flaticon.com/free-icons/bulb) is used to signify special libraries in the application.



