# House-Sales-Pricing
## 1. Overview
Welcome to my analysis. In this analysys I used various regression methods and try to predict the house prices by using them. The reason for choosing regression for the analysis is because it gives more insight about the data. In regression we look at the relation between response and explanatory variables. I will start with simple regression model then complex ones and compare the best model for the dataset.
## 2. Business Understanding
In the housing market, the understanding of factors that affect house prices is fundamental for the business.For real estate to advice there clients who are the home buyers and the home sellers they, need to look at the factors affecting the price of the homes in King County, Washington in the United States. We also provide advice to homeowners about how home renovations might increase the estimated value of their homes, and by what amount.
## 3. Data Understanding
We will use (House Sales in King County, USA) dataset for our analysis obtained Kaggle. This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.
The dataset contains 21 columns:
1 = id - Unique identifier for a house
2 = date - Date house was sold
3 = price - Sale price (prediction target)
4 = bedrooms - Number of bedrooms
5 = bathrooms - Number of bathrooms
6 = sqft_living - Square footage of living space in the home
7 = sqft_lot - Square footage of the lot
8 = floors - Number of floors (levels) in house
9 = waterfront - Whether the house is on a waterfront :Includes Duwamish, Elliott Bay, Puget Sound, Lake Union, Ship Canal, Lake Washington, Lake Sammamish, other lake, and river/slough waterfronts
10 = view - Quality of view from house :Includes views of Mt. Rainier, Olympics, Cascades, Territorial, Seattle Skyline, Puget Sound, Lake Washington, Lake Sammamish, small lake / river / creek, and other
11 = condition - How good the overall condition of the house is. Related to maintenance of house. type=r) for further explanation of each condition code
12 = grade - Overall grade of the house. Related to the construction and design of the house.
13 = sqft_above - Square footage of house apart from basement
14 = sqft_basement - Square footage of the basement
15 = yr_built - Year when house was built
16 = yr_renovated - Year when house was renovated
17 = zipcode - ZIP Code used by the United States Postal Service
18 = lat - Latitude coordinate
19 = long - Longitude coordinate
20 = sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors
21 = sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors
## 4. DATA PREPARATION
### Shape
The contains 21597 rows and 21 columns.
### Info
The dataset contains three data types in our dataset. Waterfront, view and yr_renovated has missing values.
### 5. MODELLING
I used three modelling to check the best fit for our dependent variable.
### 6. CONCLUSION
Polynomial Model was the best fit for predicting price for the dataset.
Relationship between home renovation and the price: An increase of 1 in yr_renovated is associated with an increase of about 115 in price.
