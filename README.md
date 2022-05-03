# UFOs
Utilizing JavaScript to visualize UFO sighting Data.

## Overview
In order to uncover the truth behind the existence of UFO's, sightings data is presented in a table format with filters that allow for user specifc queries for key parameters of the data. These include:

- Date
- City
- State
- Country
- Shape 

The data is stored in a javascript file and is accessed by another javascript file that forms the logic behind the behaviour of the html page as it presents the data in an interactive format. A CSS file is used to add styling elements in conjunction to the HTML file to make the webpage appear aesthetically pleasing. Thanks to Bootstrap 4's grid system, the information is presented in an organized manner and the page is mobile responsive.  

## Software
- JavaScript - ES6
- HTML5
- CSS - 2.1
- Bootstrap - 4.0  

## Results 
Searches can be performed automatically upon entering the data as the javascript file will detect a change in the input tag. This allows the user to define the search criteria and have immediate feedback with the data presented. Placeholders are filled in the input boxes that allow the user to format their serch criteria appropriately. The placeholders do not filter the data as the page will initially present the entire dataset if the user search criteria is not provided. An example search criteria is performed below: 

![filter](https://github.com/Fabalin/UFOs/blob/main/Resources/ufo_filters.PNG)

The data is presented in a table format that imports the data from the javascript file and filters using the user defined search criteria: 

![results](https://github.com/Fabalin/UFOs/blob/main/Resources/ufo_results.PNG)

## Summary 
The drawback of this webpage is that the data set contained within the page is static and new data must be added to the original javascript file manually in order have updated information regarding citings. To further develop this webpage, a javascript file should be written to append additional sources of data that can expand the available search values and allow for real-time updates to the data presented. Additionally, the data can be presented on a googlemaps api that allows the user to visually assess the spread of the sightings geographically. A more interactive dataset can uncover trends in the sightings data that can be further investigated to truly acertain the validity of UFO's. 
