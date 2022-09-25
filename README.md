# Regression-Capstone-Project
Bike Sharing Demand Prediction

Problem Statement 


Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


Data Description


The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.


Attribute Information:


Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of he day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

The Goal of this project is to develop regression models that incorporate historical usage patterns with weather, holiday, weekend data, among other criteria, to calculate the demand for rental bikes. In this project, various types regression models has been made which makes an attempt to estimate the total number of bicycles rented each hour.

we created different Regression Models in the form of linear regression, decision tree etc. we performed the Regularisation of the linear model with the help of Rigde regression, Lasso regression and ElasticNet regession.
Also, we performed the Hyper parameter tuning of decision tree model with the help of  Random Forest, Gradient Boosting and eXtreme Boosting.
Then, we evaluated all the above models with the help of Evaluation Metrics such as Mean squared error, Root mean squared error, R-square , Adjusted R-square  . 

