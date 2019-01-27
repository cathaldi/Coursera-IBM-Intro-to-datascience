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


## Methodology

As part of this assignment, after data was cleaned data the was grouped into categories of establishments. Allowing us to drill down deeper to get distributions of establishment and then visualise them.
With the counts I then created a choropleth map to help show density of establishment per city area.

## Results

The Results seem to indicate that by far the most popular type of the Dublin food sector is within the Coffee business primarily.
With over 100 establishments picked up by Foursquare. As we look down the list we see other sectors that also commonly may server a light coffee meal
such as a Sandwich Place or even some Bakeries and Delis with sit down areas.


| Establishment      | Count|
| ------------------ |:----:|
| Coffee Shop        | 63   |
| Café               | 48   |
| Restaurant         | 31   |
| Italian Restaurant | 15   |
| Sandwich Place     | 12   |
| Burrito Place	     | 11   |
| Bakery             | 10   |
| Pizza Place        | 10   |
| Deli               | 8    |

From a Location map we can see a large collection of Blue dots along Henry Street and going down further along Mary street. Which is kind of what we expect
as it's a central area and one of Dublin's busiest streets.

![alt text](https://github.com/cathaldi/Coursera-IBM-Intro-to-datascience/blob/master/couresera_dist.JPG "Locations in Dublin")


## Discusion

Going forward it seems liek it would be more beneficial to bring in data along the lines of foot traffic for the area. As mentioned within this map were 2 of Europes busiest streets with regards to foot traffic
and as such it would make sense to see what affect foot traffic has on the coffee shops in general. How far out of the way is a person willing to go to get to thier preferred coffee destination versus going to the nearest coffee place at hand.
It would also be interesting to see how much of an impact consumer loyalty has on the decision of repeat customers and if it is a weak hold.


## Conclusion
From this we can see that Dublin already has avery competitive marked that primarily serves coffee along with a very large number of establishments that could be placed within a secondary market giving consumers lots of choice with regards to the exact type of establishment they are after.
At the moment a good location seems to be at O'Connell street lower along custom house but that area seems to have far less foot traffic comapared to other streets examined.
To really give a deeper analysis more variables need to be looked at and for that reason and the above examined information it doesn't seem like a good market to enter right now.
