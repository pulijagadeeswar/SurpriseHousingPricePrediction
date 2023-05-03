# Project Name
> Surprise Housing price prediction 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual value and flip them at a higher price. For the same purpose, the company has collected a data set from house sales in Australia. The data is provided in the csv file below.

- The company is looking at prospective properties to buy to enter the market.

- You are required to build a regression model using regularization, so as to predict the actual value of the prospective properties and decide whether to invest in them or not.



The company wants to know:

  - Which variables are significant in predicting the price of a house
  - How well those variables describe the price of a house
 

## Business Goal 

 You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.



## Conclusions
- Optimal value of alpha of lasso regression is 50 and r2 score for optimal value of alpha is given below
  	R2 score for train : 0.9372405328256925
  	R2 score for test : 0.9254664123086983

- Optimal value of alpha of ridge regression is 4 and r2 score for optimal value of alpha is given below
  	R2 score for train : 0.9371096095852764
	R2 score for test : 0.9253982765709686

- Optimal value of alpha is 1 for ridge regression on variables selected by lasso regession and r2 score for optimal value of alpha is given below
	R2 score for train : 0.9392476999525955
	R2 score for test : 0.9231948226312643

-	Lasso has successfully reduced variables by shrinking the variable coefficient to 0.There are 134 variables selected by lasso regression out of 255 variables.

- From the output of both models, it is evident that Lasso does feature selection and its output is much simpler than Ridge’s, without any compromise in the accuracy over the test data. So, we should go with the lasso regression, in this case.
      


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.0
- library - numpy, Pandas, matplotlib, seaborne, sklearn, statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the business problem of Surprise Housing - A US based housing company.


## Contact
Created by [@pulijagadeeswar - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->