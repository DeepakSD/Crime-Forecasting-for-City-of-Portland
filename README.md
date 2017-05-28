# Crime-Forecasting-for-City-of-Portland

Authors: Deepak Shanmugam, Nitesh Srivatsav, Meghana Pochiraju, Suneesha Kudipudi, Vignesh Vijayakumar, Vinayaka Raju Gopal 

## Problem Statement and Approach
Crime has always been difficult to predict even with increase in technology over the years . Increase in technology has not resulted in a decrease in the number of crimes . With increase in population over the years in the city of Portland crime has also been increasing at a rapid rate. Research indicates that crimes usually occur in counties where the average per capita income is lower than the average for the entire state. These counties demonstrate a higher tendency for the number of crimes for a given instance of time. Our idea is to use the latest technologies to forecast a number(crime rate in a future instance of time) for every county(large data set) in the city of Portland so that it would benefit the local Police Department in allocating members in advance thereby preventing or minimizing damage.

## Procedure and Result
* Developed an ARIMA(Autoregressive Integrated Moving Average) model to forecast the crime rates for three categories(Low, Medium and High crime rate regions) of location ranges
* Achieved this with an accuracy of 72.12% by clustering the locations using K-Means and applied ARIMA model to all the clusters, indexed the results using Elasticsearch for efficient search and visualized with the help of Kibana

## Technology Used
Spark, Scala, Python, Elasticsearch, Kibana, Pyplot


