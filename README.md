# Rossman-Sales-Prediction
A Regression Project to Predict the sales of Rossman stores which is operational in 7 European Countries
Dirk Rossmann GmbH, commonly referred to as Rossmann, is one of the largest drug store chains in Europe with around 56,200 employees and more than 4000 stores. 
The company was founded in 1972 by Dirk Rossmann with its headquarters in Burgwedel near Hanover in Germany.


![220px-Dirk_Rossmann_GmbH](https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/Dirk_Rossmann_GmbH.jpg/800px-Dirk_Rossmann_GmbH.jpg)

**Key Points**

Data provided by Rossmann gives various information about 3,000 drug stores in 7 European countries. 

Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality.

We are provided with historical sales data for 1,115 Rossmann stores. Our task is to forecast the "Sales" column for the test set with the help of given datasets.

As the Dataset was quite large the model generalized well, and chances of overfitting and underfitting were reduced. 

In order to earn more focus company should focus more on Store d which generates the highest sales for the firm.

Gradient boosting regressor seems to be relatively very efficient with approximately 96% of r2 score. 

ordinary least square regression performed well with approximately 89% accuracy in both the train and test set, thus model wasn't looking highly biased or at high variance.

lasso and ridge didn't show any effective results in comparison to OLS

The company earns the most from Store type d thus it must maintain this and should focus more on low-performing stores like store b.

On Sunday the market might be closed, resulting in Extremely fewer sales.

The Data could also be used for Time Series Analytics but as the data is from before 2015, it is less likely for the firm to use this in future predictions.

For around 0.65 million stores the competitor is present within a range of 5KM which shows that good competition is present in most of the cases but most of the competitors are established after the year 2000.



