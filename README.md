# WPI CS573 Data Visualization Project

## Data

This project is a visualisation of [stop and search data of Kent County (UK) police](https://gist.github.com/Bizmundo/246821fffd9f3ed3c1c25f515be6eb6e).

### The Kent (UK) map
It displays the location of the stop and search on the map. It has a combo box that helps the user overlay other attributes on the map. It helps user discover whether there is a spacial correlation between the stop & search data attribute and race. 

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


![image](https://user-images.githubusercontent.com/16506192/65564970-9695f880-df1c-11e9-93f0-e0ff83f1db19.png)

## Prototypes

I’ve created a proof of concept visualization of this data. It's a bar chart that shows the proportion of the stop and search type by race.

[![image](https://user-images.githubusercontent.com/16506192/65561829-e91de780-df11-11e9-8a30-4959fcf9d725.png)](https://beta.vizhub.com/Bizmundo/f2a2654c525c466b8238c041dca5c844)



## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Is there any correlation between stop and search type and race?
 * Is there any correlation between object of search and race?
 * Is there any relationship between stop and search outcome and race?
 * Is there any spacial pattern on the location of the stops and searches?
 * How does the temporal trend of the stop and search look?

## Sketches

Below are the sketches of the charts  that will help answer the questions above.

### The bar chart
It displays the percentage or count of an attribute by race. It has a selection box that helps the user select the attribute of instrest. The selection box will have a default value as "type". Once the user clicks on the selection box, he will be presented with a list of attributes. Once the user selects an attributes, the chart will then be updated with the values of the selected attribute.
![image](https://user-images.githubusercontent.com/16506192/65564934-76663980-df1c-11e9-88f0-d5d9fc865c24.png)
### The Kent (UK) map
It displays the location of the stop and search on the map. It has a combo box that helps the user overlay other attributes on the map. The slider helps observe the trend of the spatial positions of the stop and search over time. Moving the slider from left to right will display additional locations of the stop and search on the map.
![image](https://user-images.githubusercontent.com/16506192/65564970-9695f880-df1c-11e9-93f0-e0ff83f1db19.png)

## Open Questions
I am not sure that the map of Kent is available in a format that will ease the vizulization of this data.

## Schedule of delivrables
* Get addtional data to cover one to five years of stop and search by 10/5/2019
* Data cleaning by 10/05/2019
* Gather and prepare Kent city map data 10/05/2019
* Generate algorithm to display interactive stop and search attributes bar chart 10/12/2019
* Generate algorithm to display interactive stop and search map 10/17/2019
* Validation/testing 10/25/2019
* Submission

