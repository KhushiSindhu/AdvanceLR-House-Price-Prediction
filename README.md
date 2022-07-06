# Project Name
> House Price Prdeiction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
## General Information
- #### Background:
 A US-based housing company 'Surprise Housing' has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
 For the same purpose, the company has collected a data set from the sale of houses in Australia. 
 The company is looking at prospective properties to buy to enter the market. 
- #### Business Problem:
 We need to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. We also need to determine the optimal value of lambda for ridge and lasso regression.

- #### DataSet :
  Data set gathered is collected from the sale of houses in Australia..


## Conclusions
We build various models, using Ridge and Lasso Reguralization . And choose the model with Lasso regularisation with optimal value of alpha as final model.

<h3 style = "color : Green">The below mentioned variables are Top 10 significant in predicting the price</h3>
<h4 style = "color : Green">Postive Features</h4>

- GrLivArea	              : Above grade (ground) living area square feet
- GarageCars              : Size of garage in car capacity
- BsmtFullBath	          : Basement full bathrooms
- Fireplaces	          : Number of fireplaces
- KitchenAbvGr	          : Kitchens above grade (Negative Relation)
- 1stFlrSF                : First Floor square feet
- Neighborhood_NridgHt    : Physical locations within Ames city limits: Northridge Heights
- FullBath                : Full bathrooms above grade
- Neighborhood_Crawfor    : Physical locations within Ames city limits: Crawford

<h4 style = "color : Green">Negative Features</h4>

- HouseAge	              : Difference of Year when house is sold and the year it was built.(Negative Relation)

- BsmtFinType1_No Base    : Rating of basement finished area: No Basement (Negative Relation)
## Acknowledgements
- This project is based on upgrad Course Advance Linear Regression

## Technologies Used
- Python - version 3.9.7
- Jupyter Notebook Server - version 6.4.5

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@KhushiSindhu](https://github.com/KhushiSindhu) - feel free to contact me!

