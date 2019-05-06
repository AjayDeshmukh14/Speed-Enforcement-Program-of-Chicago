# Individual Project Documentation


## Zip codes and their violations:
The general observation of zip code and their corresponding number of violations can tell us a lot about which areas have a high number of violations.

![](Images/Screenshot(85).png)

But to find the areas which are at risk due to the speed violations we should determine those areas with a high average of violations because data for some of these zip codes is recent and has less count of data.

![](Images/Screenshot(88).png)

If we compare the two graphs we can see that zip code 21869 has the highest number of traffic violations but it drops to the fourth position when we consider the average number of speed violations whereas zipcode 21861 is seventh in the total number of violations but has the highest average violations overall. 

![](Images/abc.jpg)

Revision:
* Remove gridlines: * We are just doing comparative analysis thus there is no need for gridlines, removing the gridlines will also make the graph look cleaner.
* Creation of a Dashboard: * The creation of a dashboard helps us to show a better comparison between the two visualizations.
* Addition of Textbox for description: * The addition of a caption gives a clearer idea of what is being portrayed in the graph. 
* Addition of annotations: * The addition of annotations helps us understand faster on what areas should be focused on and what is trying to be portrayed in the visualizations.

The final revised dashboard looks like:

![](Images/Screenshot(102).png)


## Violations and relation with the Quarters:
If we observe the line graphs for the zip codes with top five average violations per day we can observe that the average violations increase in Q2 and Q3 and drop in Q4 and Q1.

![](Images/Screenshot(93).png)

If we plot a line graph for all the quarters we can observe two points, overall there has been a decline in the average number of violations and also that the trend observed from the top five zip codes can be seen even for the dataset as a whole, where the average violations increase in Q2 and Q3 and drop in Q4 and Q1.

![](Images/Screenshot(94).png)

A better way to plot the graph would be

![](Images/Screenshot(90).png) 

We can see that the average violations for Q3 has been the highest for all the years and thus it is high for all the data.

Revision: 
* Rename Labels: * Renaming the label from 'Violation Date' to 'Quarter Number'.
* Add Caption: * Since we are displaying limited data on this visualization.

The final revised dashboard looks like:

![](Images/Screenshot(102).png)


## Weekday wise Average Violations change over the years:

If we see the distribution of average violations for different weekdays we can see that the violations have been high for Saturday and Sunday.

![](Images/Screenshot(99).png) 

It will be interesting to see the trend for the weekday average violations over the years.

![](Images/Screenshot(98).png) 

As we can see the average violations for each of the weekday has been consistently decreasing, which proves the program for controlling speed violations has been successful.

Revision: 
* Rename Labels: * Renaming the label from 'Violation Date' to "Days of the week". 
* Remove Gridlines: * If we are trying to observe the trend we do not nee the trend lines.
* Addition of trend lines: * The addition of trendline will be a good indicator of the reducing trend, also the trend lines are really strong which is signified by the high R-squared value and low P-value. 
* Changing Opacity: * We are trying to highlight the trend here so it is sensible to increase the opacity of the trendline and reduce the opacity for the line graph. It is imperative that we keep the line graph also because it is important to show where the trendlines are coming from and because the trendlines for all the days are almost similar.
* Addition of Caption: * The caption gives us a fair idea of how the visualization was derived.

The final revised dashboard looks like:

![](Images/Screenshot(102).png)


Tableau Public Link:
https://public.tableau.com/profile/ajay.ratnadeep.deshmukh#!/vizhome/ChicagospeedviolationsFinal/Dashboard1

References:
1.https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/gncf-3xbx
