# Data Visualization with D3.js 

This is the repository for my final project for the Data Visualization with D3.js course, which I undertook as part of Udacity Data Analyst Nanodegree.

## Tools

 1. D3.js
 2. Dimple.js

## Design

If I was doing a static chart, I would probably pick a small number of countries, create a facet plot, and show a scatterplot of BMI versus calorie consumption, encoding the years as colors on the plot. However, the power of D3.js is the ability to go *beyond* static plots.  So, I chose three variables to plot in a scatterplot, or more specifically a bubble plot.  With each bubble corresponding to an individual country, I encoded the x-axis as daily calorie consumption, the y-axis as average male BMI, and the size of the bubble as relative to that country's Gross Domestic Product (GDP) per capita.  Then, I wanted to animate through the years.  While I had data going back to 1980, I limited the data to the years 1990-2007.

## Final Insights

This visualization is an animation that shows that people in most countries increased their daily caloric consumption, as well as average body mass index (BMI), between the years 1990 and 2007.  The visualization shows each country as a "bubble" on a scatterplot, where the size of the bubble is related to that country's Gross Domestic Product (GDP) per person.  

### Rich vs Poor Countries

From the chart, it is apparent that in general the richest countries have the highest daily consumption, as well as the highest BMI, and a careful eye may discern that the richest countries have increased their consumption the most over the 18 years.  In comparison, the poorest countries, especially those in Sub-Saharan Africa, appear to still be struggling with food supply, and may be getting left behind as the richer countries become more and more overweight. 

A screenshot of the final visualization is below:
![final_viz](final_viz.png)