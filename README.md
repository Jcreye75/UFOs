# UFOs

## Overview of the analysis:
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

## What You're Creating
This new assignment consists of one technical analysis deliverable and a written report. You will submit the following deliverables:
- Deliverable 1: Filter UFO sightings on multiple criteria
- Deliverable 2: A written report on the UFO analysis (README.md)

## Resources
- Software: Git version 2.33.0.windows.2, Visual Studio 1.62.2, JavaScript and HTML

## Deliverables:
### Deliverable 1: Filter UFO sightings on multiple criteria
1. The list element that creates the button is removed, and there are five list elements for filtering in the index.html file. The resuylt is as follow:

#![5_Filter.png](https://github.com/Jcreye75/UFOs/blob/2ab010d0ab48c37769826ab9438cc71681822330/static/images/5_Filters.png)

2. The event listener was modified to detect changes to each filter in the app.js file. 
3. The updateFilters() function saves the element, value, and the id of the filter that was changed.
4. The filterTable() function loops through all of the filters and keeps any data that matches the filter values. 
5. The webpage filters the table correctly based on user input. Filters return as follows:

#![Filters_Working.png](https://github.com/Jcreye75/UFOs/blob/2ab010d0ab48c37769826ab9438cc71681822330/static/images/Filters_Working.png)

### Recommendations: 
The user must know exactly how dates, cities, or shapes are spelt in order to to a correct search.

1. The fisrt recommendation is to add a trim function which cand identify spaces upper and lower cases. So it can be easy for the user to find the correct state or city even if he does not know how it is written in the database.

2. The second recomendation is regarding the date request. Maibe it will be easier to add a calendar so the user can pickj up the date, or maybe if he only type the month and or otrher format as: mm/yy, mm/yyyy, mm, mmm. THis will facilitate the user to find the onfromation needed for UFO Sightings. 

Regards,

JC
