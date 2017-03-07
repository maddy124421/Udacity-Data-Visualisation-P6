# Udacity-Data-Visualisation-P6

###Summary

The visualization shows the survival chances across passenger’s class and gender.Interactive chart allows the viewers to find the chances of survival based on gender and Passenger class


###Design

I have used both d3.js and dimple.js to visualise the data.I used the stacked bar chart.I added survival status to classify survived and not survived.

####Chart Selections:
Stacked bar chart uses color to encode the category of data. I use it to present who survived and who did not.
Interaction is used to categorize survival based on gender and Passenger class.


Initial chart:

https://github.com/maddy124421/Udacity-Data-Visualisation-P6/blob/master/initial_chart_titanic.jpg



###Feedback
#####Friend 1

I like your charts because you can clearly see the relationships between sex, class, and survival.
No questions. It's pretty clear.
A large percent of men and class 3 passengers died.
You would not have wanted to be a third class male passenger on the Titanic.
It's clear that Survived is a binary variable, but it may be more reader friendly to indicate 1 as survived and 0 as did not survive or died.


#####Friend 2


Hi Madhu,
One quick suggestion for your consideration:
At first glance, I thought chart 1 is also about survival rate, but after a closer look, it becomes clear to me that it's actually visualizing the gender composition for each passenger class. This could be confusing since all the charts are of the same type and color scheme. There're two options. One, simply remove the top chart since that information may not be necessary to communicate to the reader; two, you can consider changing the type of visualization to make clear the difference.
Hope this is helpful.

#####Friend 3

Hi @madhu_81273961744016,
I agree with the others.
Another point I can add is that the titles of the second and last chart are overlapping.
On the y-axis may be you should be more precise like instead of write "passengers travelled" put " number of passengers travelled" for example.

###Post feedback changes

I changed the survival status from 0 and 1 to more readable format Survived and Not survived.
I changed chart title & clearly labeled axis title.
I edited the color patterns for all the charts for more understanding and differentiate from other charts. 
I also added interaction buttons for the readers to understand 
I switched from Number of Survival to Survival Rates since the amount of passengers in each class/ages group is not similar.


###Resources

dimple.js Documentation

Data Visualization and D3.js (Udacity)

mbostock's blocks

Dimple homepage

###Data
stage_1.csv: original downloaded dataset for dimple.js implementation.


