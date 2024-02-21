## Overview of Project
The purpose of this project is to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. 

## Results
Users input specific criteria into one or multiple filters: Date, City, State, Country, Shape. The updateFilters() function updates the filter variable that stores user input. And, the filterTable() function filters the table data by the user input and stores the data that matches the filter values in the variable. The webpage displays a list of results that match your search criteria. If the results are too broad, the user can add more filters and initiate a new search.

![Filter in use](https://github.com/MiracleOny/UFOs/blob/main/web/static/images/criteria_1.png?raw=true)

## Summary
One drawback of this design is that the table's length is unspecified, leaving a trail of data visible to the user. The constant visibility of the data can create a distracting visual effect, possibly affecting users who prefer a more structured and controlled webpage. Two recommendations for futher development are to enhance the User Interface. This can be done by adding client-side interactivity with JS to create a more dynamic and engaging interface. And, by implementing error messages or feedback to guide users in case of invalid inputs or other issues.
