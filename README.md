# UFO

# Overview of Project

During the eleventh week of the Trilogy University of Toronto Data Analytics & Visualization Bootcamp our Module 11 challenge is to create a written analysis with two key deliverables as follows; 

1) Deliverable : Filter UFO sightings on multiple criteria
2) Deliverable : A written report on the UFO analysis (README.md)

The tools we will be using are HTML, JavaScript, Developer Tools, VS Code, Chrome.

The files we will be using are;
*app.js,
*data.js,
*style.css,
*index.html.

Specifically,
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

![FinalModule](https://github.com/735713038455163/UFO/blob/master/FinalModule.PNG)

In this first build, a filter button was used to filter the data, and there is a date filter only.  


# Analysis

Here is the list of deliverables for the analysis of 2 deliverables:

### Deliverable 1: Filter UFO sightings on multiple criteria
- The list element that creates the button is removed, and there are five list elements for filtering in the index.html file. 
![5filters](https://github.com/735713038455163/UFO/blob/master/5filters.PNG)

- The event listener is modified to detect changes to each filter in the app.js file. 
![changelistener](https://github.com/735713038455163/UFO/blob/master/changelistener.PNG)

- The updateFilters() function saves the element, value, and the id of the filter that was changed. 
![updateFilters](https://github.com/735713038455163/UFO/blob/master/updateFilters.PNG)

- The filterTable() function loops through all of the filters and keeps any data that matches the filter values. 
![filterTable](https://github.com/735713038455163/UFO/blob/master/filterTable.PNG)

- The webpage filters the table correctly based on user input. 

### Deliverable 2: A written report on the UFO analysis 
-(README.md)

## Results
Now, thanks to research generously funded by W. Avy, a UFO-enthusiast and amateur ufologist, we can supplement our sky-searching with data analysis. This data visualization project,  will help raise awareness of the ubiquity of sightings.

### To perform a search 
1) Data is entered into the fields, and good luck sorting!. Without a list of input variables, and syntax structure how would you know what to type into the fileds?  

![fields](https://github.com/735713038455163/UFO/blob/master/fields.PNG)

2) Then information is displayed filtered.
![Final](https://github.com/735713038455163/UFO/blob/master/Final.PNG)

# Summary

The first build had a filter button that had to be clicked to display the results, which was the strenght for the build, but also added an additonal step. If the user didn't click the button it would not display. For the challenge build, we removed the button and added 5 more filter elements. This not only made the code more complex, it made filtering more complex for the user. Sometimes simple is better. 

Some limitations of the dataset are that the data sample is small and pulling from data.js file which is limiting the data to historical data. For example, what if we created an input field on the website to ensure we captured more data from anyone wishing to report sigthing online.
Additional recommendations for futher development would be to seek other websites that have more data. Either connect via API or conduct webscraping to bring in the data. The more worldly and realtime data the more facinating it would be. Also if we could tag the realtime sighthings to actual people via thier social media sites this would create a network of see'ers and believ'ers. Are we alone in the universe? 

