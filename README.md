# UFO Sightings Webpage


### Project Overview
The purpose of this project is to create an interactive webpage that displays UFO data (JSON) in tabular format
and filters the data on the following criteria: date, city, state, country, and shape (by utilizing the d3 JS library).


### Results
The webpage includes a series of filters on the left side of the table that displays UFO data.
The user may filter the UFO Sightings table by inputting text into the filter boxes on the left
side of the table. 

The table will be iteratively filtered to match the criteria that the user entered.
For example, one can start by entering a state such as "ca" in the "Enter a State" box.
![First Filter](https://raw.githubusercontent.com/Dreski9000/ufo_sightings/main/static/images/filter_1.png)

Then the user can proceed to further filter the results by city such as "San Diego".
![Second Filter](https://raw.githubusercontent.com/Dreski9000/ufo_sightings/main/static/images/filter_2.png)

The user can narrow the results even further by entering a shape such as "triangle" into the shape input box.
![Third Filter](https://raw.githubusercontent.com/Dreski9000/ufo_sightings/main/static/images/filter_3.png)

### Summary
One drawback of the webpage in its current state is the UX / User Interaction element that is not strictly intuitive.
Two possible ways of improving the user-friendliness would be:
 * Use drop-down filter with a limited set of possible values
 * Perform the filter-search as the user is typing by partially matching the strings.
