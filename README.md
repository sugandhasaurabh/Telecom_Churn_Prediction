# Housing Sales Price Analysis
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

 1. Which variables are significant in predicting the price of a house, and

 2. How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.




## Table of Contents
* [General Info](#general-information)
* [Business Goals](#business-goals)
* [Model Building](#model-building)
* [Steps For Model Building](#steps-for-model-building)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
 1. Which variables are significant in predicting the price of a house, and
 2. How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

## Business Goals
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Model Building
The model has to be built using Ridge and Lasso regression and the optimal value of Alpha has to be identified. Both the model has to be compared andbest model has to be selected. Also, top predictor variables has to be identified.

## Steps for Model Building
1. Reading and Understanding Data
2. Visualising the Data
3. Data Preparation
4. Data Transformation (Log Tranformation)
5. Splitting the Data into Training and Testing Sets
6. Building the Model Linear regression, Ridge and Lasso
7. Making predictions using final model
8. Comparing the models

## Conclusions
Lasso Regrssion should be applied. The top 5 predictor variables are:
1. GrLivArea
2. OverallQual_Excellent
3. Neighborhood_StoneBr
4. OverallQual_Very Good
5. Functional_Typ




## Technologies Used
Below python libraries were used:
- pandas
- numpy
- matplotlib
- seaborn
- calender
- sklearn
- statsmodels
- scipy



## Acknowledgements
Created by Sugandha Saurabh | github - @sugandhasaurabh


## Contact
Sugandha Saurabh | github - @sugandhasaurabh


