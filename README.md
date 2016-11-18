# About
#### Forecast Profits for Clothing Sales - sample uses a TimeSeries predictive model trained on recent purchase history of men's clothing to forecast profits for the next 4 time periods or a Streaming TimeSeries self-learning model to dynamically learn how to predict the next 4 time periods based on past purchases by women. Both take a input of sales data on a current time period to make their prediction.

# Prerequisites
#### Models available in \model subdirectory (catalog_timeseries.str, catalog_streaming_timeseries.str) have to be uploaded to the Watson Machine Learning instance using Dashboard (drop box). Make sure that uploaded models are named correctly (contextID). 
#### catalog_timeseries.str --> catalogTS
#### catalog_streaming_timeseries.str --> catalogSTS

#### For reference please see screenshot below.

![alt text](https://cloud.githubusercontent.com/assets/23261116/20431592/26f8e448-ad9b-11e6-9a2a-191fb913630b.jpg "Dashboard")


#### After successful models upload deployed application should provide scoring capability as shown below.

![alt text](https://cloud.githubusercontent.com/assets/23261116/20431696/befa68f2-ad9b-11e6-884c-185abe6feb09.jpg  "Application")
