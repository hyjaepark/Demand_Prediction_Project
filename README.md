# Opex-competition
Anomaly Order Detection and Response

# Main Objective
The main purpose of this project was to predict times when inventory does not meet demand due to high influx of orders referred to as "cuts".

# Explatory Data Analysis
## Graph shows cuts over time 
<img src="plots/plot1.JPG" width="500" height="300">

## Products that has the most cuts
<img src="plots/plot2.JPG" width="500" height="300">

## Cuts by distribution center
<img src="plots/plot3.JPG" width="500" height="300">

## Cut drops by increasing inventory by fixed amount
<img src="plots/simple1.jpg" width="500" height="300">

<img src="plots/simple2.jpg" width="500" height="300">

<img src="plots/simple3.jpg" width="500" height="300">

## Seasonality

<img src="plots/plot4.png" width="500" height="300">

<img src="plots/plot5.png" width="500" height="300">

# Modeling
## Features created/used

* On Hand Inventory / Change of Inventory
* Pageview Out of Stock
* Average Price / Change of Price
* Consumer Ordered Units
* Forecast 1,4,8 Weeks 
* Difference in Forecast & Consumer Order Units

## Classification models & results
| |Logistic Regression | Randomforest | XGboost | 
|--- |------------- | ------------- | ------------- | 
| F-1 Score  | 0.6456 | 0.7122|  0.75|
