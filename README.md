# House-Price-Prediction Assignment From UpGrad & IIITB. A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:
 
Which variables are significant in predicting the price of a house, and

 How well those variables describe the price of a house.

 

Also, To determine the optimal value of lambda for ridge and lasso regression.

[Conclusions] ### Final Verdict: These are the final features that should be selected for predicting the price of house Hence the equation: Log(Y) = C + 0.131(x1) + 0.112(x2) + 0.049(x3) + 0.038(x4) + 0.033(x5) + 0.027(x6) + 0.018(x7) + 0.017(x8) + 0.009(x9) + 0.007(x10)+ 0.006(x11) + 0.006(x12) + 0.006(x13) + 0.004(x14) + 0.001(x15) - 0.089(x16) + Error term(RSS + alpha * (sum of absolute value of coefficients). INFERENCE: Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house. The higher values of positive coeeficients suggest a high sale value. Some of those features are:- Feature Description: GrLivArea Above grade (ground) living area square feet OverallQual Rates the overall material and finish of the house OverallCond Rates the overall condition of the house TotalBsmtSF Total square feet of basement area GarageArea Size of garage in square feet The higher values of negative coeeficients suggest a decrease in sale value. Some of those features are:-
Feature Description PropAge Age of the property at the time of seeling MSSubClass Identifies the type of dwelling involved in the sale. When the market value of the property is lower than the Predicted Sale Price, its the time to buy.* 


## Contact
Created by [ABHI8896@github]