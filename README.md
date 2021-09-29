# Forecasting-the-Real-Estate-Price-using-ML
This machine learning project uses fundamental machine learning techniques to estimate the selling price of a new home using data on housing prices.
## Objective
The majority of consumers are inexperienced when it comes to choosing a place to stay. Since the demand fluctuates, making the right choice to buy a property and paying the right price is critical. The aim of the paper is to accurately predict the market value of a residential property leveraging the machine learning techniques for regression. <br/>
## Data Description
The dataset for this project is obtained from Kaggle which contains Bangalore house prices data comprising  prices of houses across different places in Bangalore. Dataset also consists of information about area, bhk, number of bathroom and several other attributes. Each row contains fixed size object of features. There are 9 features and each feature can be accessed by its name having 13,321 records.  

##### Features:
1. Area_type – describes the area
2. Availability – when it can be possessed or when it is ready(categorical and time-series)
3. Location – where it is located in Bengaluru (Area name)
4. Size – in BHK or Bedroom (1-10 or more)
5. Society – to which society it belongs
6. Total_sqft – size of the property in sq.ft
7. Bath – No. of bathrooms
8. Balcony – No. of the balcony

##### Target variable:
- Price – Value of the property in lakhs(INR) <br/> Source dataset: https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data
## Models
Three models were compared to check for maximum efficiency based on researching related works. They are,

- Linear Regression
- XGBoost
- Random Forest Regressor
## Evaluation Metric:
- Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted price value and the logarithm of the observed sales price.
- Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.

## Conclusion
Random Forest produces a least root mean square value among other chosen models and thus concluded as the best performer in prediction of real estate cost value.

