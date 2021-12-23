# Data visualization
Data visualization has become a key aspect to know how to get the most out of information, helping to make decisions in a prescriptive way.

In this repository I will present some tools to use to develop more understandable graphs.

---
- Matplotlib
- Plotly (Interactive plots)
- Mapping
---

## Matplotlib
Layering, Faceting and Transformations
### 1.
Highlight how the events described below have affected the call money rate (TGT).
- 1973-11: Oil Price Shock
- 1991-01 - 1993-12: Recession in Switzerland
- 2009-01 – 2009-12: Recession in Switzerland
- 2008-09: Lehman-Brothers collapse
- 2011-08: Introduction of CHF/EUR floor
- 2015-01: Removal of CHF/EUR floor

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/Swiss_economy.png"/>
</p>

---

### 2.
Analyze the daily deaths in France over the last 20 years and highlight the biggest anomalies found in the data.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/mort_france.png"/>
</p>

---

### 3.
Compare the Engine Size versus the highway fuel efficiency, to know if there is a correlation between this two variables.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/Engine_Size_highway.png"/>
</p>

**Faceting** can be used to show more data, provide context, and make a visualization easier to undersatand.

That's why based on the same concept as the previous exercise, we are going to separate the results according to the type of car model involved.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/Engine_Size_highway_type.png"/>
</p>

---

### 4.
Data transformations can make a chart easier to understand and are necessary to even be able to present the data in some cases.

Having the data of the dosage of antibiotic (mic or minimum inhibitory concentration in μg/ml) necessary to kill various bacteria, and the gram-type of each bacterium, we are going to analize which is the dosage necessary of penicillin to achieve the 'mic' for the each bacteria.

Considering that the required dose difference is very large among the different bacteria, it is necessary to apply a transformation, in this case the logarithmic transformation.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/hist_transf.png"/>
</p>

Based on the same idea of the previous exercise, we are going to analize something similar but with more than one antibiotic and using a heatmap to visualize it.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/heatmap_transf.png"/>
</p>

---

---

## Plotly
Plotly produces interactive graphs, can be embedded on websites, and provides a wide variety of complex plotting options. The visuals are of high quality and easy to read and interpret.
### 1.
In this first exercise, we are going to analyze a dataframe with records for bills and tips in a restaurant for several days and types of clients.

- Plot a boxplot comparing tips distribution for category smoker.
- Plot a scatter plot with the total bill in the x-axis and the tip in the y-axis.
- Plot a bar chart with the total bills (y-axis) per day (x-axis). Use a trace per sex.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/restaurant.png"/>
</p>

---

### 2.
Analyze a dataframe of records of different species of flowers with records for different characteristics.

- Plot a scatter plot grouping by the specie of flowers.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/iris.png"/>
</p>

---

### 3.
Using a dataframe used before, the cars one, we are going to analyze the cars from the 70's and 80's, to realize the relation of each of them between the weight and the miles per gallon.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/miles_weight.png"/>
</p>

---

### 4. Plotly Express or PX
This dataframe shows so much information about different countries.

- Plot the relationship between the gross domestic product (GDP) and the life expectancy per country per year, and also grouping by continent.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/life_exp.png"/>
</p>

---

---

## Mapping (Choropleth)
Choropleth Maps display divided geographical areas or regions that are coloured, shaded or patterned in relation to a data variable. This provides a way to visualise values over a geographical area, which can show variation or patterns across the displayed location.

To build a choropleth map, there are 2 mandatory files:
- A dataset with the information you want to display
- A GeoJSON file with the delimitation of the areas to plot

Geographic JSON (or GeoJSON) is an open format for encoding simple geospatial datasets using the JSON (JavaScript Object Notation) standard. It is used to describe data such as points, lines, strings, polygons, as well as sets and subsets of these data types, and to add non-spatial information attributes.

---

### 1.
The dataset consists of a GeoJSON object, containing the polygons defining the shape of each district. There is also a dataset contaning the elections results for each district of Montreal.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/montreal_elect.png"/>
</p>

---

### 2.
This dataset gives us information about the unemployment rate of the whole USA.

<p align="center">
  <image src="https://github.com/wanaguirre/data_visualization/blob/main/Notebooks/images/usa_unemployment.png"/>
</p>

---
