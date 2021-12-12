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
  <image src="https://user-images.githubusercontent.com/83764392/145720415-381f2578-466b-4fe6-88bf-40f1129a2226.png"/>
</p>
---

### 2.
Compare the Engine Size versus the highway fuel efficiency, to know if there is a correlation between this two variables.

<p align="center">
  <image src="https://user-images.githubusercontent.com/83764392/145720876-d2bf83fc-4c0f-4372-a25b-3d76a0214a76.png"/>
</p>

**Faceting** can be used to show more data, provide context, and make a visualization easier to undersatand.

That's why based on the same concept as the previous exercise, we are going to separate the results according to the type of car model involved.

<p align="center">
  <image src="https://user-images.githubusercontent.com/83764392/145721006-a1ecae50-83ac-4f9a-bfc4-54b215435ba5.png"/>
</p>
---

### 3.
Analyze the daily deaths in France over the last 20 years and highlight the biggest anomalies found in the data.

<p align="center">
  <image src="https://user-images.githubusercontent.com/83764392/145721232-0d7d81b0-0b26-458c-bb0f-3f5c32d2f2cb.png"/>
</p>
---

### 4.
Data transformations can make a chart easier to understand and are necessary to even be able to present the data in some cases.

Having the data of the dosage of antibiotic (mic or minimum inhibitory concentration in μg/ml) necessary to kill various bacteria, and the gram-type of each bacterium, we are going to analize which is the dosage necessary of penicillin to achieve the 'mic' for the each bacteria.

Considering that the required dose difference is very large among the different bacteria, it is necessary to apply a transformation, in this case the logarithmic transformation.

<p align="center">
  <image src="https://user-images.githubusercontent.com/83764392/145725635-bd2b64a7-6e7d-4acc-af5d-345ca0a1b0b2.png"/>
</p>

Based on the same idea of the previous exercise, we are going to analize something similar but with more than one antibiotic and using a heatmap to visualize it.

<p align="center">
  <image src="https://user-images.githubusercontent.com/83764392/145725748-97c5f120-9b4c-4fed-b616-61b34730df1d.png"/>
</p>
---

## Plotly
