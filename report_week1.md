# Introduction
In this [assignment](https://www.coursera.org/learn/applied-data-science-capstone/peer/60zST/capstone-project-the-battle-of-neighborhoods-week-1/submit) I plan to try and break down current distribution of cafés and resteraunts within a 10 minute walk of Dublin City Center
with the aim of resolving a location for a new coffee shop using with the reuirement of using the Foursquare API.

## Business Problem

Dublin is already a busy city with a lot of existing cafés and restaurants, our aim is to see can we find a location that has relatively less competition while still keeping us 
very close to the city centre. 

Reasons for O'Connell  street:

1. O'Connell  street was chosen for this as it is a Central bus route for both Dublin Bus, and various tourist buses constantly touring the city.
2. Both Luas (Tram) lines intersect on O'Connell street
3. The Street is located close to both Henry Street and Grafton Street which are both in the [top 20 busiest streets measured by footfall](https://www.realestate.bnpparibas.com/pan-european-footfall-2017-2018) in Europe (Page 7)
4. Close to tourist attractions such as Guiness storehouse, Dublin Castle and Templebar.



## Data
The data used in this project comes primarly from the [Foursquare API](https://developer.foursquare.com/). A list of 20 prominant streets within a 10-15 minute walk of O'Connell street was chosen
and queried against Foursquare.

The data was used to help get a view of the current competitive scene such as:
- a breakdown of existing competition
- location and distribution of the competition
- a choropleth map to show the relitive comparison of competitors per city block.

Additionally a [geojson file was generated](https://github.com/cathaldi/Coursera-IBM-Intro-to-datascience/blob/master/dublin.geojson)   with [geojson.io](http://geojson.io) for use in a chronopeth map which is also included.
