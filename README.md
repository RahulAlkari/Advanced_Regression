# Advanced_Regression
### Project : 
A US-based housing company named Surprise Housing has decided to enter the Australian market. 
The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
For the same purpose, the company has collected a data set from the sale of houses in Australia which has been provided.

The company is looking at prospective properties to buy to enter the market. 
We are supposed to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

Which variables are significant in predicting the price of a house, and  How well those variables describe the price of a house. Also, determine the optimal value of lambda for ridge and lasso regression.

### Business Goal 
You are required to model the price of houses with the available independent variables. 
This model will then be used by the management to understand how exactly the prices vary with the variables. 
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

### Findings :
1) A Model is created using lasso and Ridge regression. Optimal values for Ridge is 200 while for Lasso it 0.02.
2) The five important variables that describe the price of the house are :
    OverallQual,     GrLivArea,    BsmtFinSF1,    TotalBsmtSF,    GarageArea
3) A Lasso model with 0.8918 accuracy is suggested over the Ridge as it is much simpler and robust.


