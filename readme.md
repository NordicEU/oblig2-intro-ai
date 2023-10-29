### We chose the first task: "Predict stock market price for TESLA."

***

We decided to use a regression algorithm because
1. The goal is to predict a continonous value
2. Stock price prediction models involves regression metrics such as MSE, RMSE, MAE
3. Better for predicting numerical value

### Why we chose to start our dataset from 2018 and onwards instead of using data all the way back to 2010
***

Our regression algorithm really struggled to predict data in the latest year because of bias from the low values from the early years.

We solved this by starting our training set from 2018, this is roughly a year before the big spike in value of the stock.

