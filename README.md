# Real Estate-Investment---Prediction and Risk Analysis


## Introduction:
The last few years has seen a housing market driven partly by narrowing of home available on the market and low mortgage rates. According to CFRA Research’s Global Director of Industry and Equity Research, Ken Leon, strong growth in the housing market was driven by higher levels of consumer confidence, higher household income, and employment growth. Since home growth is expected to level-off soon, Syracuse Real Estate Investment Trust (SREIT), may be wondering where their best bet chance investing in the United States is.

The goal of this study is to predict which zip codes provide the best investment for the Syracuse Real Estate Investment Trust (SREIT). In addition, we wanted to narrow down our results for SREIT to three final zip codes that would be the best investment opportunity.

## Analysis:
### Data Pre-Processing: Importing Datasets and Cleaning

For our analysis we imported the housing data described below from the following [link](http://files.zillowstatic.com/research/public/Zip/Zip_Zhvi_SingleFamilyResidence.csv)
• House dataframe– a .csv that had data about ZHVI (Zillow Home Value Index). Interestingly, because of the encoding of this excel file, we had to specify when importing the file that it was a “"ISO-8859-1” encoding.

To learn more about the dataset, we used the information provided on the [Zillow data's site](https://www.zillow.com/research/data/)

The data is about ZHVI (Zillow Home Value Index). According to the website, the ZHVI is a smoothed, seasonally adjusted measure of the typical home value and the market change across a given region and housing type.

The data has 30,415 rows (see Figure 1) and 293 columns. Each individual row contains a region within a county in the United States. The columns "RegionName" is denoted by that regions zipcode. The first 6 columns are related to the region/county/state/city/metron name information. In general, the raw data is sorted by in ascending order by the SizeRank column. The Zillow website does not specifically state what the parameters or definitions of this column are. It is likely that this number either is related to the average ZHVI per square foot for that region across all the years, the regions proximity to urban centers. Therefore, the highest ranked cities based on SizeRank have the largest available ZHVI per sq foot for potential urbanization. These smaller regions are typically close to city centers but have higher home value indices.

For the data types of the columns: there are 260 columns that are float64, 29 that are int64, and 4 columns that are object.


[Click Here To View the Report And Results](https://github.com/ParInsights/Real-Estate-Investment---Modeling-Project/blob/master/Predicting_Best_RealEstate_Investment_Location.pdf) 
