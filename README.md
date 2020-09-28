# BEST ZIP CODES TO INVEST



![zipcodes_to_invest.png](attachment:zipcodes_to_invest.png)


## Problem Statement

The purpose of this project is to provide 5 best zip codes to invest in real estate. Zillow monthly median price data from 1996 to 2018 will be used for this analysis.

__Filtering the zip codes:__

The real estate market is known for its ups and downs with the ever-changing economic conditions. To choose the best zip codes, some of the main factors which affects the housing price are analyzed using census data. These factors are Population growth,Job growth,Rent index & Vacancy rate. The average rate of increase(ROI) for the last 4 years was calculated. Among the states with high ROI those with high population growth , job growth & rent index & low vacancy rate was filtered.

## The Dataset
The dataset have the following features:

- Region id
- Region name
- City
- State
- Metro area
- County name 
- And the Median prices from 1996 to 2018

##### External data sources links
- https://www.bls.gov/news.release/laus.nr0.htm
- https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html#par_textimage 
- https://www.census.gov/housing/hvs/files/annual18/ann18t_3.xlsx vacancy rate
- https://www.usatoday.com/list/news/50-states/monthly-rent-by-state/6edf40b2-ca12-4902-84df-522c46b8f029/?block=texas - rent index

 

# How to Navigate Jupyter Notebooks

> __Order of Navigation:__
- __Part I   :__ Jupyter Notebook: __Best_Zipcodes_to_invest - Best_Zipcodes_to_invest
.ipynb__
- __Part II  :__ Power point pdf : __Time series analysis 5 zip codes - Time series analysis 5 zip codes
.pdf__
- __Part III  :__ data : __Zillow_data - _Zillow_data
.csv__

# Learning Concepts and Tools

__Data Science Concepts Used:__
- Time series analysis
- Data Mining
- Data Visualization
- Data Cleaning
- Data Exploration


__Tools Used:__
- Time series ARIMA model
- Matplotlib 



# Project Summary

## Problem Description
The fluctuating price in real estate market put investors at risk of losing money. We try to lower the risk by analyzing the factors affecting the market and selecting the areas with low risk and high profit.

## Rate of Increase

ROI was calculated for each year from 2015 to 2018 and then the average was used to select the top zip codes. 

__Top zipcodes with the highest rate of increse__
![high_roi_zipcodes.png](attachment:high_roi_zipcodes.png)

__Population growth,Job growth& Vacancy rate__
![zipcode_growth.png](attachment:zipcode_growth.png)

__Rent index__

![zipcode_rent_index.png](attachment:zipcode_rent_index.png)

# Best Zip Codes | Conclusions

The analysis, shows the best zip codes to invest are: 

> __Key Findings__
- zip code 27980 Hertfold, NC
- zip code 30032 Candler-Mcafee,GA
- zip code 33805 Lakeland, Fl
- zip code 32117 Holly Hill,Fl
- zip code 95134  San Jose , CA
- zip code 28208  Charlotte , NC

# Best zip codes to invest | Recommendations

The prices were analyzed using time series and zip code 95134 is exclude from the list of zip code due to model accuracy and the rest 5 zip codes are finalized. the model has wider confidence interval beyond 2021. So that we will be forecasting and using the next 36 months only. The rate of increase is calculated between 2018 & 2021 for each zip code and according to the the ROI value the following is recommended:  

__For the following zip codes with high ROI by 2021 , rent the house for a while & sale it when the price go up__
 
  
- Zip code 28208 Charlotte, NC , ROI of 73% by 2021

- Zip code 33805 Lakeland, Fl ,ROI of 78% by 2021

- Zip code 30032 Candler-Mcafee,GA ,ROI of 76% by 2021



__Due to the lower ROI by 2021 remodeling and selling is the best choice for the following zip codes__
- Due to the lower ROI by 2021 remodeling and selling is the best choice

- Zip code 27980 Hertfold, NC , ROI of 45 % by 2021

- Zip code 32117 Holly Hill,Fl ,ROI of 56% by 2021
