# Bike-Demand-Prediction

Problem Statement
Currently, Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
Here we need to explore and analyze the data to discover key factors responsible for rental bikes and come up with ways/recommendations to increase the demand for rental bikes

Tags: 

Links:
Project presentation: slideshow

Dataset 1: Seoul Bike Data

Data Description:
The source dataset is in ‘txt’ format with ‘.csv’. 
The dataset contains 8760 rows and 14 columns. Out of the total, 14 Columns are independent variables and 1 is the dependent variable. There are no missing values for the provided input dataset. Rented Bike Count is the number of total rentals and is the dependent variable.

Steps Involved:
Following are the steps involved in the exploratory data analysis. 
Data Preprocessing: The pre-processing of data involves data cleaning, handling missing values, and data transformation.
Data Visualization: The visualization of data is done to uncover the essential patterns and trends between variables.
Data Interpretation: It involves finding patterns and analyzing the dependency of variables.
Data Modeling: It involves splitting data into train and test and applying different models and checking accuracy by analyzing summary.
Conclusion: Involves the entire summary of our project which includes interpretation of data and selection of optimal models. 

Conclusion 
 In this study, we understood that a lot of Koreans rent bikes during the weekdays, so we guessed that the fundamental use is by either students or working professionals to follow the usual schedule. There are additionally many conditions that add to the variety of other things like the day of the week, the time of the day, and climate conditions. From the project we can 

The number of bikes rented is more on working days as compared to on holidays.
The number of Rented Bikes is more in Summer Season followed by Autumn & Spring and Winter being least of all
The Demand for bikes is huge in the months of May, June, and July and there’s a drop in the months of December, January, and February. 
The demand for bikes is huge during summer and it’s the other way during winter.
The demand is high during the morning and evening hours.
we can infer that the temperature and the dew point temperature are correlated.

We have applied Linear Regression Model for the given data set. We get RMSE as 444 and Adjusted R square as 52 % which is not closer to 100 % . Hence this model is not the best fit for the given problem statement. We have applied the Decision Tree Model for a given dataset. We get RMSE as 299 less than Linear Regression and Adjusted R square as 78% which is closer to 1 as compared to linear regression. Hence this model is a moderate fit for the given problem statement. We have applied Random Forest Regressor for the given dataset. We get RMSE as 207 less than Decision Tree and Adjusted R square as 89% which is closer to 1 as compared to Decision Tree . Hence this model is a good fit for the given problem statement.

After a detailed comparison of how our models are working, we can see that Random forest is producing better results when compared to the other ones for the given dataset. 



