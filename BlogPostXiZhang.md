BlogPostXiZhang
====================
# Part I The study of NY biopharmaceutical cluster industry from 1998 to 2010
## Overview
Understanding cluster industry is very important for regional economics. As is known, the natural geographical condition is state. However, state is a more robust concept. Actually, for different industries, contributions vary from section to section inside a state. Hence, I use another more specific geographical concept here, that is economic areas. I'll focus on biopharmaceutical industry for different economic areas which belong to NY state and explore the relationship of employment share for each economic area for different years to find the trend of development of biopharmaceutical industry and the most important economic area of NY state.

## Procedure
### Dataset
Here, I use data from the website US Cluster Mapping. We focus on the value of employment share which is a measure of the relative cluster presence in a particular location to the nation. I can get employment share of different economic areas for each year. The data itself is clean. The only thing I need to do here is to merge them by year.

### Introduction to ECharts
A fantastic visualization tool I find is ECharts which is developed by Baidu data team. It is easier to start than D3 though it may be less free to add more own creative graphs, but is obviously enough for frequently-used analysis. Actually, you can combine different charts, make dynamic charts, and do some statistical manipulation of the data on the plot. For example, if you create a pie chart here, you can drag one sector onto another sector to calculate their sum. The original code is written using javascript and can be easily applied into modular program.

### Application

In this case, I use categorical variable year as the x axis and numeric variable employment share as the y axis. I combine bar, line and pie charts to explore the data from three different perspectives of view.

You can click[MyPlot](https://github.com/xizhang0831/radsketch_/blob/master/demo.html) to see the visualization result. On the lower right corner, you can use the toolbox to switch between line chart, bar chart and stacked bar chart. 

### Part of the code for drawing the plot
![pcode](https://raw.githubusercontent.com/xizhang0831/radsketch_/master/pcode.png)
Here I use html but call back packages written using javascript
### Result 
Through the plot, we can find that the trend is the biopharmaceutical industry of NY state has been in a decline from 2002. Besides, New York absolutely takes the dominant position on biopharmaceutical industry of NY state.

## Improvement for part I and some tasks still in progress
Firstly, I want to add map to part I in the next step to see the cluster degree of different regions in a more general and macro view.
Secondly, data I used here is easily to get and has been cleanly formatted, so I want to use python to scrap different data from website for part II and do some analysis.