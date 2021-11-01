# An Analysis of Kickstarter Theater Campaign Data

## Overview of Project

This project is centered around an analysis of data from Kickstarter campaigns.

### Purpose

The purpose of this project was to collect data on campaigns for the funding of plays, display outcomes from the analysis and draw conclusions from the findings.

## Analysis and Challenges

The analysis based on launch date began with the creation of a pivot table showing outcomes by month the campaign was created that can be filtered by the year the campaign was created and by the subcategory of the campaign. This pivot table ws used to create a line chart that displayed successful and failed campaigns trends across the year.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/18372229/139624971-425a6a53-d737-4b8d-b82c-b31aef5d9996.png)


The analysis of campaign outcomes based on goals began with the creation of a table using the COUNTIFS function in excel to populate the cells and count the number of successful and failed campaigns based on specific goal ranges. This table was then used to create a line chart that displays the percentage of successful and failed  campaigns across the range of goal amounts.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/18372229/139624984-8714c376-1787-4575-a324-06b3b1f06924.png)


### Analysis of Outcomes Based on Launch Date

One conclusion that can be taken from the analysis of outcome based on launch date is that successful and failed campaigns follow a similar general trend, spiking and falling in the same months. Another simple conclusion that can be taken from the data is that the most successful month of the year to launch a theater campaign is May and the least successful is December.

### Analysis of Outcomes Based on Goals

A conclusion that can be made about the theater outcomes based on goals data is that the campaigns at the lower end of the range of goal amounts are generally much more successful than those in the higher end on average.

### Challenges and Difficulties Encountered

A challenge I faced in this assignment is getting used to the COUNTIF function syntax. I was confused about the criteria format at first.

Obviously we could create table and graphs for different subcategories of campaigns but I think an interesting plot would show the relationship between backer count and pledge total filtered by category.

