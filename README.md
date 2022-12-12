# Washington State Library Finder

## Project Description
For our final project we have built a sort data by distance application to allow our users to identify nearby libraries to their location at the University of Washington.  We have included a web map that locates all the libraries in the state of Washington. The base map that we created for our application has a monochrome theme that highlights the streets. We have then included our libraries in point format as a layer on top of the base map. Each library has an icon that distinguishes the main purpose of each library. Hovering over each library will display a popup of the library containing information such as its phone contact number, their website, long/lat location, city, county, and any other relevant information that helps our intended audience better choose the library for their needs. There is a search bar in the upper left hand corner of the map that allows users to type in their address and discover the library that is closest to them. Once a user types in and selects their address the map will zoom to their address and show the highlighted library that is closest to them with information on that library. 
## Project Goals 
Libraries are very resourceful locations for students during the research process. However, we feel that they often get overlooked for research purposes these days due to the accessibility of resources online. By creating a convenient tool that helps users find libraries in Washington state nearby them and the focus or purpose of each one we hope that they will use the libraries more. 

## Application Url: 
https://soriabjo.github.io/geog495_libraryfinder/index.html

## Screen Shots: 

## Data Sources:
We have settled on using data provided by Washington Geoservices and accessed through the [Washington Geospatial Open Data Portal](https://geo.wa.gov/datasets/f62ef46873bd4a80a31e3e88eafa43eb_0/explore?location=47.311825%2C-120.841168%2C7.40). This dataset provides coordinates for each library, as well as identifying information and key descriptors.

## Applied Libraries: 
The applied libraries that we used for the purposes of this project are Mapbox GL’s Javascript and CSS libraries. We also used the Mapbox Geocoder plugin and Turf.js, which allowed us to be able to calculate the distance between the user and the various libraries. To host our application on a website, we use GitHub Pages.

## Acknowledgments: 
We would like to give thanks to our professor, Dr. Bo Zhao, and our teaching assistant, Steven Bao, for teaching us the necessary tools and concepts throughout the quarter in order for us to complete this project successfully.

## Other Info: 
In order to complete this project, we followed a various tutorials from Mapbox, [Build a store locator using Mapbox GL JS](https://docs.mapbox.com/help/tutorials/building-a-store-locator/) and [Sort stores by distance](https://docs.mapbox.com/help/tutorials/geocode-and-sort-stores/). 
 
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



