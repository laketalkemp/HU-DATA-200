# Data Visualization
Statistical data collected must be processed and presented in a form that benefits users. Data visualization tools help users draw insights from the data. Data visualization is the pictorial or graphical representation of qualitative and quantitative data in visual aids such as charts, graphs, maps, and tables.  

### Basic Charts
Commonly used charts to illustrate raw data.
1. Bar Chart. Rectangles of equal width that represent a set of attribute data.  The relative height of the bar is proportional to the frequency of occurrences of the attributes.

2. Pie Chart. A circle with several sectors, one with proportional width to the frequency of the attribute data.  

3. Histogram. Frequency distributions are represented as several rectangles, one for each attribute.  The width of the rectangles is proportional to the width of the class interval, while the height of the rectangles is proportional to the frequencies.  Successive attribute class intervals are positioned next to each other.

4.  Box Plot.  Displays the measures of central tendency as five values depicting the spread of the data.  The minimum is seen as the rectangle's base; the maximum is the top of the rectangle, and the three quartiles are seen as Q1, Q2, and Q3. Please remember that Q2 is equal to the median.  Outliers are depicted as trailing points connected by whiskers to the box plot.

### Advanced Charts
1.  Scatter Plot. A display of several pairs of observations to highlight the relationships between two sets of data.  The scatter plot indicates whether data is scattered or where there is clustering as a band.  Scattered data suggests that the variables are unrelated.  A band implies that there is relatedness between the variables.

2. Bubble Chart.  An extension of the scatter plot was used to determine the relatedness of three variables.  The size of the bubble indicates variations in the third variable.  The larger the bubble, the greater the variation in the third bubble.  The spread of the variables is seen as spread across the axis.  An upward-sloping band would indicate a relationship in which as one variable increases, the second also increases.

### Interpretation of Charts
* Characteristics of the charts give insight into the relatedness of the data.  The heights of bars in the bar chart and areas of sectors in the pie charts are proportional to the frequency.  Larger sections or taller bars are larger values occurring more frequently.  
* Histograms of variable data are analyzed for patterns. Visually recognizing the presence or absence of a pattern can be helpful.  
* Degrees of symmetry can show skewness and degrees of spread, showing the degree of uncertainty in the data. The shape of the distribution in the graph shows the centering of the data.  
* The Presence of Outliers is seen in data points that have an impact but are not representative of typical patterns. This is also seen in the box plot, demonstrating the extreme values as whiskers placed a significant distance between the first and third quartiles as the magnitude of variation.  
* Scatter plots can be used to determine the relatedness of the variables.  The degree of scatter is seen as the clustering of data into bands or the spacing apart. 

### Selecting the Appropriate Chart
The visualization's requirements determine the type of chart to use. This includes incorporating the scope of the study and determining the information to be depicted.  

Qualitative and Attribute Data are best presented with a bar graph or pie chart. These charts communicate the relative frequency at which each attribute occurs, and they are limited to a single characteristic per chart.

A histogram communicates the relative frequency of measurable or quantitative variable data.  

Variable Data uses many data projections to display each of the statistic values.  A box plot demonstrated the extreme values, maximum, minimum, and the three quartiles as a visual display.

The chart should be a scatter plot or bubble chart for multiple data sets with different characteristics.

### Storytelling with Charts
* It is essential to include the scope and purpose of the study with each chart.  
* Carefully decide the variable to be studied.  
* The link between data collection and chart construction can be displayed as data from measurements or attribute data.  
* Identify heterogeneity in the Data sets using separate chart types for homogenous data.  
* Include information to be communicated to the user, such as excluding sample values as outliers.  
* Sample size and collection period give the user more information about the data.

![chartDecisionTree](https://www.analyticsvidhya.com/wp-content/uploads/2015/05/Chart_Selection.jpeg)

### The Figure basics

`fig = plt.figure()             # an empty figure with no Axes`<br>
`fig, ax = plt.subplots()       # a figure with a single Axes`<br>
`fig, axs = plt.subplots(2, 2)  # a figure with a 2x2 grid of Axes`<br>
`# a figure with one Axes on the left, and two on the right:`<br>
`fig, axs = plt.subplot_mosaic([['left', 'right_top'],`<br>
                              ` ['left', 'right_bottom']])`<br>

![VP](https://matplotlib.org/stable/_images/anatomy.png)

## **Violin Plot**

- Violin plots are similar to box plots, but they also display the data's probability density at different values.
- It is a numeric data plotting approach that combines the box and kernel density plots.
- It is more informative than a box plot.
- In general, while a box plot only displays summary statistics including mean, median, and interquartile ranges, a violin plot displays the entire data distribution.
- The width of each curve corresponds with the approximate frequency of data points in each region. 

### **Analysis of the Violin Plot vs. the Boxplot**

![VP](https://labcontent.simplicdn.net/data-content/content-assets/Data_and_AI/Applied_Machine_Learning/Images/0.5_Exploratory_Data_Analysis/Trainer_PPT_and_IPYNB/VP.png)

Visit the documentation for more on how to create violin plots: https://matplotlib.org/stable/gallery/statistics/boxplot_vs_violin.html#sphx-glr-gallery-statistics-boxplot-vs-violin-py
