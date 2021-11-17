# Data-Science-Project
Predicting the Price of Used Cars in Saudi Arabia.
Abstract:
The main purpose of my project is to try to predict how used cars will perform so we can help people in Saudi Arabia with how the price will be. Around 1 in 5 cars of the car parc (15 years) was transacted in the Used Car market in 2019. In comparison, for 1 new car sold 2.5 used cars (under 15 years) are sold each year. This ratio is likely to grow in favor of used cars in the next 5 years. First, we made the detailed exploratory analysis. We have decided which metric to use. We analyzed both target and features in detail. We transform categorical variables into numeric so we can use them in the model. We transform numerical variables to reduce skewness and get close to normal distribution. Baseline Model, in our case, RandomForestRegressor model, without and scaling and transformation did a quite a good job. We looked at the results of each model and selected the best one.

Design:
Used cars are very different beasts with huge uncertainty in both pricing and supply. Keeping this in mind, the pricing scheme of these used cars becomes important in order to grow in the market. With machine learning models would enable us to come up with a pricing model that can effectively predict the price of used cars and can help the business in devising profitable strategies using differential pricing.

Data:
The purpose of this project is to predict the price of a car based on the features in the data. Data taken from Kaggle Website(https://www.kaggle.com/reemalruqi/used-cars-in-saudi-arabia). The dataset contains 8035 rows with 9 features, and the features are: Make,Model, Year, Origin, Gear Type, Mileage, Region, Options, Price. However, Processing Years to Derive Age of car to understand how old cars is and its effect on price.so creating a new column Age in total of 10 columns. 
Now, most of the data concerned and be used for the project are Price. Other data such as Make, Year, Mileage can be used to have an overview of the data. However, in this project I will predict the continues value (Price) which is a regression problem.

Algorithms:
We have developed model to predict car price problem.
First, we made the detailed exploratory analysis.
We have decided which metric to use. We analyzed both target and features in detail. We transform categorical variables into numeric so we can use them in the model. We transform numerical variables to reduce skewness and get close to normal distribution. We looked at the results of each model and selected the best one. 

Models:
As predicted in EDA, Price is an important factor in Car Price Prediction. We have obtained 75% Accuracy using Random Forest. We have obtained 35% Accuracy using LinearRegression. We have obtained 29% Accuracy using KNeighborsClassifier.

the entire training dataset of 5492 records was split into 80/20 train vs. holdout, and all scores reported below were calculated with 5-fold cross validation on the training portion only. Predictions on the 20% holdout were limited to the very end, so this split was only used, and scores seen just once.


Tools:
•	NumPy and Pandas for data manipulation
•	Scikit-learn for modeling
•	Matplotlib and Seaborn for plotting
•	Tableau for interactive visualizations




 



