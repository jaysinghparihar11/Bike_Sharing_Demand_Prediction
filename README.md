# Bike_Sharing_Demand_Prediction

# Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Dataset Description
• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# Steps
Reading and Understanding Data Visualising the Data Data Preparation Splitting the Data into Training and Testing Sets Feature Scaling on the train data Building the Model Residual Analysis of the train data Making predictions using final model Model Evaluation

# Conclusions


I started with data wrangling, then I performed exploratory data analysis (EDA) on all the variables in the dataset. During the analysis, I observed some skewness and applied the np.sqrt function to make my dependent variable normally distributed. Additionally, I conducted EDA on both my continuous variables and categorical columns.

I used three machine learning models—Linear Regression, RandomForestRegressor, and XGBoost. Among them, XGBoost performed the best in our models.That's why i want to use XGboost algorithm for my future prediction.
