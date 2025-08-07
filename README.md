# KSA Real Estate Analysis
Analysis of real estate market trends in Saudi Arabia to identify high-performing properties based on profitability, demand, and location.\
Group 3; Mariam Taj Muhammad & Rabab Kaddad

## About Dataset
The data was accessed from Kaggle:https://www.kaggle.com/datasets/lama122/saudi-arabia-real-estate-aqar\
The dataset is collected and scrapped from Aqar website: https://sa.aqar.fm/

### Context

The goal of this statistical analysis is to help us understand the relationship between house features and how these variables are used to predict the house price.
The chosen cities are Riyadh, Jeddah, Dammam, and Al-Khobar

    Riyadh is the capital and largest city in Saudi Arabia, with the largest municipal population in the Middle East. Riyadh has a diverse range of people and cultures, it is still growing day by day.

    Jeddah which located in the middle of the eastern coast of the red sea and is considered the economic and tourism capital of the country.

    Dammam it lies on the Persian Gulf northwest of Bahrain Island and forms a larger metropolitan and industrial complex with Khobar, Qatif, and Dhahran.

    Al-Khobar city is one of the three main cities in the Eastern Province, the others being Dammam and Dhahran. It is developing into an important industrial city, with factories turning out industrial gas, dairy products, carbonated water, tissue paper and ready-made garments.

This dataset will only focused on the rental houses.
### Content

-city: city where house locate in.\
-district: district where house locate in.\
-front: What is the house front is north, west .. etc.\
-size: size in m^2.\
-property_age: property age for the house.\
-bedrooms: number of bedrooms.\
-bathrooms: number of bathrooms.\
-livingrooms: number of livingrooms.\
-kitchen: show whether the house have a kitchen or not.\
-garage: show whether the house have a garage or not.\
-driver_room: show whether the house have a driver_room or not.\
-maid_room: show whether the house have a maid_room or not.\
-furnished: show whether the house is furnished or not.\
-ac: show whether the house have a ac or not.\
-roof: show whether the house have a space for roof on top or not.\
-pool: show whether the house have a pool or not.\
-frontyard: show whether the house have a frontyard or not.\
-basement: show whether the house have a basement or not.\
-duplex: show whether the house is a duplex or not.\
-stairs: show whether the house have a stairs or not.\
-elevator: show whether the house have an elevator or not.\
-fireplace: show whether the house have a fireplace or not.\
-price: show the price of the house.\
-details: shows any additional details from the house owner about the house.\


## Problem Statement
The real estate market in Saudi Arabia is complex, and property prices vary a lot due to many factors.
However, missing or inaccurate data makes it hard to know the real value and compare different regions.

## Aim
To identify key factors that influence real estate prices in Saudi Arabia.
Especially across Riyadh, Dammam, Khobar, and Jeddah.

## Tools
Python: Data Cleaning, analysis, and visualization.\
Jupyter lab & Google Collab: to access python.\
Excel: Data analysis.\
Canva: Presentation.\
Trello: Project Planning.\


## Assumptions
Prices assumed to be in SAR.\
Some properties with 0 kitchens; the kitchen column was assumed as extra kitchens.\
Some properties were considered as duplex, but had neither stairs no elevators; these data points were assumed incorrect and eliminated.\
Size of the properties as 1 m²  and 95000 m² ; assumed incorrect and eliminated.\

 
## Dataset
1. Understanding the Dataset\
    What is the size of the dataset (rows and columns)?\
    What are the data types of the features (categorical, numerical, date)?\
    Are there any missing values, and how much of the data is missing?\
    Are there outliers that may represent errors or extreme properties?\
2. Property Characteristics\
    What is the distribution of the number of bedrooms and bathrooms? \
    What is the distribution of property sizes (square feet or square meters)?\
    Are there common patterns in floor plans or building age? (?)\
3. Price Analysis\
    What is the distribution of property prices?\
    How does price vary with property size? (Price per square foot/m²)\
    Are there price outliers (luxury or urgent sales)?\
4. Location Insights\
    Which locations or neighborhoods have the highest and lowest average prices?\
    Are there clusters of high-value properties geographically?\
    How does proximity to landmarks or city centers affect price?\
5. Correlation and Relationships\
    Which features are strongly correlated with property price?\
    How do location, size, and property type interact to affect pricing?\
    Does newer construction or renovation year impact price significantly?\
6. Advanced/Optional Questions\
    Can we segment the market into clusters (luxury, affordable, mid-market)?\
    What is the price distribution per property age group (new vs. old)?\
    Is there a relationship between amenities (pool, parking, balcony) and price?\

 

