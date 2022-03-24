# Telecom Churn Prediction
> In the telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers. It is very important for any telecom operator to prevent the present customers from churning to other operators. As a data scientist, your task in this case study would be to build an ML model which can predict if the customer will churn or not in a particular month based on the past data.

The main goal of the case study is to build ML models to predict churn. The predictive model that you’re going to build will the following purposes:

It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.

It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.




## Table of Contents
* [General Info](#general-information)
* [Business Goals](#business-goals)
* [Model Building](#model-building)
* [Steps For Model Building](#steps-for-model-building)
* [Technologies Used](#technologies-used)
* [Recommendations](#Recommendations)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
In the telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers. It is very important for any telecom operator to prevent the present customers from churning to other operators. As a data scientist, your task in this case study would be to build an ML model which can predict if the customer will churn or not in a particular month based on the past data.

## Business Goals
The main goal of the case study is to build ML models to predict churn. The predictive model that you’re going to build will the following purposes:

a. It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
b. It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.

Even though overall accuracy will be your primary evaluation metric, you should also mention other metrics like precision, recall, etc. for the different models that can be used for evaluation purposes based on different business objectives. For example, in this problem statement, one business goal can be to build an ML model that identifies customers who'll definitely churn with more accuracy as compared to the ones who'll not churn. Make sure you mention which metric can be used in such scenarios.
 

## Model Building
1. Telecommunications industry experiences an average of 15 - 25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has become even more important than customer acquisition.
2. Here we are given with 3 months of data related to customer usage. In this case study, we analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.
3. In the Telecom Industry, approximately 80% of revenue comes from the top 20% customers (called high-value customers). Thus, if we can reduce churn of the high-value customers, we will be able to reduce significant revenue leakage. Hence, this case study focuses on high value customers only.
4. The dataset contains customer-level information for a span of four consecutive months - June, July and August. The months are encoded as 6, 7 and 8, respectively.
5. The business objective is to predict the churn using the data (features) from the first three months.
6. This is a classification problem, where we need to predict whether the customers is about to churn or not. We have carried out Baseline Logistic Regression, then Logistic Regression with PCA, PCA + Random Forest, PCA + XGBoost.
7. Once the Best Fit model is identified, the churn can be predicted. And important 10 features can be identified which can be used for recommendation to retain High Value Customers

## Steps for Model Building
1. Reading And Understanding Data
2. Data Cleaning and Preparation
3. Exploratory Data Analysis
4. Data Pre-Processing
5. Modelling
6. Churn Prediction
7. Recommendations

## Recommendations
1. The telecom company should be focussing more on better plans, features and products which is customer specific such that the customer average revenue increases.
2. The customer is also churning due to bad network issues. The company should try to improve the network so that the overall customer experience is good. This aslo includes roaming services as well.
3. The company should also improve their connectivity with other networks to improve the offnet usage, which eventually will bring better user experience.
4. The company should also plan to improve local network and try to bring in more people under same network such thet local calls under same network is increased. They can bring in referral plans to invite more customers into their network.



## Technologies Used
Below python libraries were used:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- prettytables

## Acknowledgements
Created by Sugandha Saurabh | github - @sugandhasaurabh


## Contact
Sugandha Saurabh | github - @sugandhasaurabh


