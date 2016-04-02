# FlightDelays

The goal of this document is to use the US Dept. of Transportation on-time arrival data for non-stop domestic flights by major air carriers to predict arrival delays. We will build a binary classification model for predicting arrival delays. 

The data can be found [here](http://transtats.bts.gov/Tables.asp?DB_ID=120&DB_Name=Airline%20On-Time%20Performance%20Data&DB_Short_Name=On-Time). I chose to use data from January 2016 and January 2015.

In this notebook, we try three classification models: logistic regression, a random forest, and LDA. They all show roughly the same behavior: the AUC in all cases was roughly .64. Looking forward, I would like to download 12 months of data. My intuition is that the month of the year is meaningful because it is an indicator of weather (when taken into account with departure airport).
