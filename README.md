# D3 Homework - Data Journalism and D3

![](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

I accepted a data visualization position for a major metro newspaper. I took it upon myself to analyze the current trends that shape people's lives, as well as create interactive charts, graphs and elements to help readers understand their findings.

The editor wants to publish a series of articles on the health risks faced by certain demographic groups.
So I have taken it upon myself to get the first insight into the story by examining information from the US Census Bureau and the Behavioral Risk Factor Surveillance System. 

The data set included with the assignment is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml) The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

## The Task

### Core Assignment: D3 Dabbler (Required Assignment)

![](Images/4-scatter.jpg)

I created a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

Using the D3 techniques, I created a scatter plot that represents each state with circle elements. The code this graphic are in `app.js` file and I used the data from `data.csv` using the `d3.csv` function. 

* I Included state abbreviations in the circles.

* Created and situated my axes and labels to the left and bottom of the chart.


- - -

### Bonus: (Optional Assignment)

I created dynamic graphic using D3 lets all plots interact with the data.

![](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

I Placed additional labels in the scatter plot and give them click events so that the users can decide which data to display. I Animated the transitions for the circles locations as well as the range of your axes. I created three  risk factors for each axis. 


#### 2. Incorporate d3-tip

I added information about the circles and where I show information with the data that the user has selected, for which I used the `d3-tip.js` plugin developed by [Justin Palmer]

![](Images/8-tooltip.gif)

- - -


### Copyright

Jose Luis Duarte © 2021. All Rights Reserved.
