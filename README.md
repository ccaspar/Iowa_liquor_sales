# Iowa Liquor Sales Analysis

|Table of Contents |
|---|
| [Overview](#overview) |
| [Data](#data) |
| [Key Insights](#key-insights) |



## Overview
This project conducts and analysis of alcohol transaction data in Iowa to assess which locations in Iowa are the best to open a liquor store. I combined liquor data with demographic data to test if demographic data could predict total store sales. Because I want to infer about the relations between my variables and my target, regression is an appropriate method to use. In this instance, I want to find the optimal demographic measures and then locate the areas with the best combinations of these features.


## Data
Two datasets were used: Iowa liquor transactions, and Iowa demographic data.
- Iowa liquor transactions:
	Provided by the state of Iowa, consists of every class E liquor transaction in Iowa from January 2015 to March 2016. Data includes store info and address, liquor type and quantity, and cost to store and buyer.

- Iowa demographic data:
	Pulled from the Iowa State Data Center, a combination of demographic data organized by county. Data was pulled from the 'American Community Survey' section of the ISDC's website.


## Key Insights
Sales data is very informative of and highly correlated to total sales volume, particularly bottles sold. This was not a unexpected conclusion. On the other hand, demographic data exhibited surprisingly poor explanatory power on total sales by store, with very low r-squared values and significance levels.




## Concepts and Skills used
Python <br>
Pandas <br>
SKLearn <br>
Statsmodels <br>
Matploblib <br>
Multiple Linear Regression <br>
Model cross-validation <br>