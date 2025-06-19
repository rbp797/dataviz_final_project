# Data Visualization 

> Rene Perez. 

## Mini-Project 2

This Data-visualization project is composed of California Housing Prices from the 1990 Census of the State of California.

1. [California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices.)


The objective is to make use of the toolset and principles of data visualization, displaying and uncovering trends, patterns, tendencies, and outlieres, using ggplot for R, this report will create:

1. Data trasnformation using functions like, filter, select, group_by and other.

2. Bar charts,line charts, and others.

3. Scatter plots, histograms.

4. Dashboards.

5. Gggplot is the library used

6. Coding language is R.

7. Rstudio is the integrated development environment.

8. For spatial visualization the package is SF.

9. Fitting of a Linear Regression Analysis.


### **Data Visualization.**


![California housing](./figures/base2.svg)








### **Executive Summary (Linear Regression Analysis)**

1. The model fits reasonably well (R² ≈ 0.65).

2. Most variables are statistically significant.

3. median_income is the strongest positive predictor.

4. Location features (longitude, latitude, ocean_proximity) are very important.

5. Population and housing structure (rooms, households) affect value but may be entangled in multicollinearity[^1].


### **Linear Regression Output**





<table style="text-align:center"><tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="1" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td>median_house_value</td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">longitude</td><td>-26,812.990<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(1,019.651)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">latitude</td><td>-25,482.190<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(1,004.702)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">housing_median_age</td><td>1,072.520<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(43.886)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">total_rooms</td><td>-6.193<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.791)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">total_bedrooms</td><td>100.556<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(6.869)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">population</td><td>-37.969<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(1.076)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">households</td><td>49.617<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(7.451)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">median_income</td><td>39,259.570<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(338.005)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">ocean_proximityINLAND</td><td>-39,284.300<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(1,744.258)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">ocean_proximityISLAND</td><td>152,901.900<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(30,741.880)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">ocean_proximityNEAR.BAY</td><td>-3,954.052<sup>**</sup></td></tr>
<tr><td style="text-align:left"></td><td>(1,913.339)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">ocean_proximityNEAR.OCEAN</td><td>4,278.134<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(1,569.525)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td style="text-align:left">Constant</td><td>-2,269,954.000<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(88,013.880)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>20,433</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.646</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.646</td></tr>
<tr><td style="text-align:left">Residual Std. Error</td><td>68,656.950 (df = 20420)</td></tr>
<tr><td style="text-align:left">F Statistic</td><td>3,111.608<sup>***</sup> (df = 12; 20420)</td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"><em>Note:</em></td><td style="text-align:right"><sup>*</sup>p<0.1; <sup>**</sup>p<0.05; <sup>***</sup>p<0.01</td></tr>
</table>



[^1]:Multicollinearity happens when two or more predictor variables in a regression model are highly correlated with each other. This means they contain overlapping information, which makes it hard for the model to determine which variable is actually influencing the outcome.
