# Data-Visualization
A visualization about the flow of Eritrean refugees in the world. This project was part of Udacity's Data Analysis course

# SUMARRY

This visualization is intended to show the steady flow of Eritrean refugees in the last 15 years. The map shows how the refugee population is distributed across the world while the chart plot at the bottom is country specific. The users can interact with the visualization to look into his country or year of interest. While its left to the reader to draw his/her own conclusions here are some of the takeout’s:

 1) Overall, the Eritrean refugee population across the world has been increasing steadily.
 2) The number of Eritrean refuges in Europe has increased sharply in the year 2013 & 2014.
 3) The refugee level in the neighboring countries (Sudan and Ethiopia) has decreased in 2012-2014.
 
## DESIGN
The plan was to create visualization on the flow of Eritrean refugee across the world. The initial thought was to represent the refugee population in each country using a circle. The radius and color of the circle would represent the size of the population (double emphasis). To make it more visually appealing, I intended to represent the flow of each refugee by a curve/line that will ultimately fade out.
As is seen in the ‘line plus circle.html’ the line plot didn’t come as appealing. Even if you fade it out, the plot is too crowded and so I decided to lose that from the final plot. 
The final viz incorporates comments from students, friends and Udacity mentor. The color of the country is used to represent the number of Eritrean asylum seekers in that country in that year. Hovering your mouse on the country of interest shows the country name and asylum seekers. You can click any of the year buttons on the left to investigate the year of interest. 
Included is also line-scatter plot used to show the trend in each country over the 15 years.

#### Animation
The visualization will animate through the years 2000-2014. 
#### Background Color and Color Gradient 
The refugee population in each country is represented by *"#ffffcc","#c2e699","#78c679","#31a354","#006837"** color gradient. Five color scales are used because of the data set seem to be roughly grouped in to five categories (0-500,500-3000,3000-1000,10000-13000). However, there was one an outlier with more than 30,000. To include that in the representation and at the same time not to affect the granularity, five scales were used (0-654, 655-3274,3275-13096.13906-32740).
These four colors are choosen to give maximum granualarity. 
Through out the visualization, I have refrained from red and deep blue colors so as not to make the figure color saturated.However, I have decieded to use a BLACK background color. This is beacause we normmaly assciate black color with death or bad news and that is the messege I was planning to transmit. The fact that a country of just 6 million continous to cause its citizen to be refugess at such a large scale is definetely heart breaking.
#### Year Buttons 
Year buttons are used to allow the user to look at a specific year of interest. Those are used so that the users can interact with the plot and draw his/her own conclusions.
#### Tool Tips
Whenever, the user hover’s the mouse on the country, the country’s name and the population size will come. This is meant to provide the reader with the exact information. In addition, the title will be updated with the year that is currently under investigation.

#### ERITREA is colored **RED**
To identify Eritrea from the rest of the world, it is colored red.  This change is made as a result of a feedback. Red is sued to make the country distict from all other colors used in the map.
#### Info button
I have included an info button on the top-right side of the screen. On click, a basic information about the plot and possible interactions are explained. This is intended to make the vizualization easy to understood.
#### Source link
A source link is included. Initially, clicking the source button was opening the link in the same window, clearing out the visualization. After a feedback from one of the students, I made sure the link opened in a new tab.The source link is included incase the user wants to access the data.
#### Line-Scatter plot
A friend wanted to investigate how the refugee population has changed over the years in Netherlands. As it stands you will have to click each year button and hover your mouse over the country of interest each year.
 To make it easier, I included a plot with a dropdown menu for each country. So you can select the country of interest and you will have the trend over the years presented in a scatter plot with a line chart.  
#### Y-Axis 
The Y-axis of the scatter plot was initially on a linear scale. Looking at the data, most of the refugee population is less 10000. But also there is an outlier with around 32000 and some around 13000. To make the visualization more clear, I decided to change the scale to log.But then I got a comments from Udacity mentors that this could more appealing if it was a dynamic linear scale and that is what we have in the final vizulation. The Y-scale changes depending on country choosen.
#### Tooltips
Hover your mouse on the dots with the chart and it will give you the exact X and Y axis values. This is the reason why the dots were included along with the line plot.

## FEEDBACK
1.	Clicking on your "source" button, takes you away from your graph, and forces a reload. I think you want to open a new window with the source site. (*Incorporated this feedback on the final viz*)
   
2.	I will look for it, but I don't really know where Eritrea is. Which one is it? Should you highlight it? I only have the idea that it is close to Ethiopia and Somalia. (*Incorporated this feedback on the final viz*)
3.	Maybe asking too much, but because it is hard to see some of the points when the number of refugees is small, Could it be possible to draw arrows joining Eritrea and each receiving country, perhaps with the width representing the volume? I would like to know how this can be done. And perhaps some patterns can emerge, like one wave staying in Africa, other going mainly to Europe, other to America, or Asia, etc…

*This was not included in the final viz*

    That's  a good idea. In fact, initially I was planning on drawing an animated line for each person and that way build the circles. But that proved to be a lit bit too complicated. Moreover, what happened is the lines started to obscure each other, especially in Europe. The countries are very close to each other that drawing a line started to make the visualization a bit busy. I am not sure if it answers the question you had but below the map, there is a second plot (scatter plot) intended to show the trend within each country. So you select a country and see how the Eritrean refugee population in that country has changed over the years.
4.	Hi @mb842x, you use circle size to show the scale of the refugee, and it looks like you also use color for the same purpose. could one of the patterns be used to show other info? I think it's very good visualization but just throw in some quick feedback. (*In the final viz, only the color of the country is used to indicate the refugee population*)

5.	Can you do something to make it easier to see the country wise trend? (*Incorporated this feedback on the final viz*)



 

