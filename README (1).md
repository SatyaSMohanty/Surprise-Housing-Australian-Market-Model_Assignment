Surprise Housing Australian Market Model
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.
- Train.CSV

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The important varibale are: GrLivArea, GarageCars, BsmtFullBath, TotalBsmtSF, MasVnrArea, Fireplaces
OverallQual, FullBath, CulDSac, WoodDeckSF, 2ndFlrSF, LotArea, YearBuilt, OverallCond, YearRemodAdd, RL
HalfBath, RL, GarageYrBlt, RL
- Lasso is a better method for model selection.
- Optimal value of Lambda for Ridge is 0.2 and Lasso is 0.0001



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- panda
- sklearn
- matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->