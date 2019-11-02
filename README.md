# WPI CS573 Data Visualization Final Project

## Data

This project is a visualisation of [stop and search data of Kent County (UK) police](https://gist.github.com/Bizmundo/246821fffd9f3ed3c1c25f515be6eb6e).


## Questions & Tasks

This visualization project attempt to help the user answer the following questions:

 * Is there any spacial pattern on the location of the stops and searches?
 * How does the temporal trend of the stop and search look on the map?
 * Is there any correlation between stop and search type and race?
 * Is there any correlation between object of search and race?
 * Is there any relationship between stop and search outcome and race?

### The Kent County (UK) police stop and search interactive map
It displays the location of the stop and search on the map. It has a combo box that helps the user overlay other attributes on the map. It helps user discover whether there is a spatial pattern between the stop & search data attribute and race. 

The race dropdown menu contains:
* All
* Asian
* Black
* Mixed
* Other
* White

The filter dropdown menu contains:
* Type 
* Part of a policing operation
* Gender
* Legislation
* Outcome
* Outcome linked to object of search
* Removal of more than just outer clothing
* Removal of more than just outer clothing


![image](https://user-images.githubusercontent.com/16506192/68064378-19b32700-fcf1-11e9-8355-069db00dfce2.PNG)
 <p>Figure 1: Kent County (UK) interactive police stop and search map</p>

-The interactive map above can be found on [vizhub.](https://beta.vizhub.com/Bizmundo/eeae1f30537140e4a1594886d048a7fb)
-The map topojson data used to create this map can be found on [github.](https://gist.github.com/Bizmundo/6217aa9331f15c6d92ce6bb2797f18a9)
-The search and stop data used to create this map can be found on [github.](https://gist.github.com/Bizmundo/246821fffd9f3ed3c1c25f515be6eb6e)

## Future Works
### The Kent County (UK) police stop and search interactive map
A time range selector will be added the interactive map to enable users to filter the stop & search data by time. This will enable the user to discover any spcial trend over time. 

### Linked proportion bar chart
This  bar chart will be linked to the stop and search map. It will display the proportion the user selected attribute by race. This will helps the user determine whether the attribute of the arrest are proportionally balanced between race.
[![image](https://user-images.githubusercontent.com/16506192/65561829-e91de780-df11-11e9-8a30-4959fcf9d725.png)](https://beta.vizhub.com/Bizmundo/f2a2654c525c466b8238c041dca5c844)
<p>Figure 2: Stop & search type by race</p>









