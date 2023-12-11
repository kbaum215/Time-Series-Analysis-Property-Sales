# ADS506_GroupProj

To run the full code, use the file final_project.RMD. 

We each did one model that are in the following order in the file: Holt-Winters, ARIMA, SARIMA. 

Here are the libraries that are used:

library(readr)
library(tidyverse)
library(dplyr)
library(ggplot2)
library(lubridate)
library(zoo) 
library(mice)
library(corrplot)
library(forecast)
library(fpp2)
library(ggfortify) 
library(xts)

Below is a description of the data problem from Kaggle:
https://www.kaggle.com/datasets/htagholdings/property-sales/

Context
A multivariate time series has more than one time-dependent variable. Each variable depends not only on its past values but also has some dependency on other variables.

We have accumulated property sales data for the 2007-2019 period for one specific region. The data contains sales prices for houses and units with 1,2,3,4,5 bedrooms. These are the cross-depended variables.
