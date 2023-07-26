# Advanced regression housing price assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

 

Also, determine the optimal value of lambda for ridge and lasso regression.

 

Business Goal 

 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- What is the background of your project?
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
- What is the business probem that your project is trying to solve?
> The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.
- What is the dataset that is being used?
> Train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Answer- The below mentioned variables are significant in predicting the price
- LotArea------------- Lot size in square feet
- OverallQual--------Rates the overall material and finish of the house
- Year remodelled------When was the house remoddeled
- Central air -----  if the house has centrally airconditon or not
- Lot shape --- shape of the lot 
- Garage finish ---- how well was the garage finished 
- Bedrooms above grade ---- How many bedrooms were above grade 
- Basmentexposure ------ Refered to walkout or garden level walls 
- BsmtFinSF1-------Type 1 finished square feet

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- import numpy as np
- import pandas as pd
- import seaborn as sns
- import matplotlib.pyplot as plt
- from sklearn import linear_model, metrics
- from sklearn.linear_model import LinearRegression
- from sklearn.linear_model import Ridge
- from sklearn.linear_model import Lasso
- from sklearn.model_selection import train_test_split,GridSearchCV,KFold, cross_val_score
- from sklearn.feature_selection import RFE
- from sklearn.preprocessing import StandardScaler,MinMaxScaler
- from sklearn.metrics import mean_squared_error, r2_score
- import os
- import warnings

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@sk1499] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
