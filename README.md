# Tule-Data-Analysis

### Data Cleaning and wrangling:

This script performs cleaning steps including: removing NA values, and eliminating tower ids that should not belong in the analysis. It also performs a merge to combine all the cleaned data into one dataframe. 

### Data Visualization:

This script plots some of the important metrics so we can get a better idea of the structure and range of the data. Violin plots are used to show pri and actual max canopy values by region and year.

### Basic Statistics:

Basic statistics are generated in this script. Including generating a dataframe containing average maximum canopy date by crop with standard deviation values. This is also plotted. This script also contains a function which calculates the local minima and maxima for each tower id. 

### Statistical Methods and Forecasting:

The first statistical method used in this script is a simple linear regression to predict maximum canopy date using all other variables as predictors. The predicted values are plotted next to the actual values to show how close or far they are from each other. 

This script also creates an ARIMA which is used to forecast pri values across dates by region. This model can be used as a template for building other ARIMAs on different metrics, however it does a very good job with predictions for pri value by region. 
