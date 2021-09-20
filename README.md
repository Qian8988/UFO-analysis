# UFO-analysis


Module 11 Challenge

## Overview of Project
In order to provide a more in-depth analysis of UFO sightings , we need to create an HTML page that we can pull up information from a javascript data file.  Table filters for the city, state, country, and shape are needed to be added.

## Results: 

Filter UFO sightings on multiple criteria

Using JavaScript and HTML, modify the code in index.html file to create more table filters. Add filters for the city, state, country, and shape, as shown in the following image

<img width="796" alt="1" src="https://user-images.githubusercontent.com/86527347/133950913-71378614-bcf5-452c-88e2-feddd9d2e7b3.png">


## Summary: 

Using JavaScript and HTML, I've modified the code in index.html file to create more table filters. 
The handleClick() function in app.js file has been replaced with a new function that saves the element, value, and id of the filter that was changed. Then, created a new function to loop through the dataset and keep only the results that match the search criteria. The webpage is updated with the search criteria after pressing "Enter".

One drawback about this design is that it is not so easy to decide what parameter should be used for the filtering. Users need to go through the table a find the parameter desired for the analysis. 

My two recommendations for improving this website would be: firstly, a button to clear all the input fields might be need, and secondly, a site that updating the data adding might be needed.
