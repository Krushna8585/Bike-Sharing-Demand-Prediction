# Bike-Sharing-Demand-Prediction
 Bike Sharing Demand Prediction

-----------------------------------------------------
💾 Table of Content

    Introduction
    Abstract
    Dataset Information
    Problem Statement
    Conclusion

-----------------------------------------------------
📖 Introduction:

    In this dataset, the bikes are rented to the public every hour.

    As a result, it is important that the rental bike is ready and available to the public at the correct time, as this decreases wait times. Maintaining a consistent supply of rental bikes for the city eventually becomes a major challenge.

    As a result, our main goal is to predict the number of bikes required at each hour in order to maintain a stable supply of rental bikes.

    To do so, we'll need to build a model that will predict numbers of rental bikes at each hour.

    As a result, the dataset consists of various features, some of which will play a major role in predicting the dependent variable, i.e. the number of rental bikes.

image

-----------------------------------------------------
📖 Abstract:

    The goal of this project is to combine the historical bike usage patterns with the weather data to forecast bike rental demand. The data set consists of hourly rental data spanning two years.

    Exploratory Data Analysis is done on the dataset and compares the target variable with the other variables to find the distribution of the graph.

    This information includes information about the host, lodging prices, and reviews, among other things.

    We look for null values which were not found and outliers.

    We also perform correlation analysis to extract out the important and relevant features from the dataset and later perform a train test split to train the model.

    The main objective is to build a predictive model, which could help to train a model to predict the number of bike rentals per hour given the weather conditions.

    This would in turn help to predict quickly and efficiently.

-----------------------------------------------------
📖 Dataset information:

    Date: year-month-day

    Rented Bike count - Count of bikes rented at each hour

    Hour - Hour of the day

    Temperature-Temperature in Celsius

    Humidity - %

    Wind Speed - m/s

    Visibility - 10m

    Dew point temperature - Celsius

    Solar radiation - MJ/m2

    Rainfall - mm

    Snowfall - cm

    Seasons - Winter, Spring, Summer, Autumn

    Holiday - Holiday/No holiday

    Functional Day - (Non-Functional Day), Fun (Functional Day)

-----------------------------------------------------
📖 Problem Statement:

    The main objective is to build a predictive model, which could help to train a model to predict the number of bike rentals of the year given the weather conditions.

    This would in turn help to predict quickly and efficiently.

-----------------------------------------------------
📖 Conclusion:

    Since loading the data, we've done null value treatment, data transformation, data skewness, outlier removal, multicollinearity removal, label encoding, feature engineering, and finally feature selection.

    We have implemented three models, such as Linear Regression, Polynomial Linear Regression and Random Forest Regressor In which our linear regression model was underfitted, the polynomial regression model failed to deliver satisfactory results.

    We then implemented the random forest regression model, which resulted in an overfit model.

    On the random forest regression model, we performed hyperparameter tuning using grid search CV to overcome such problems.

    As a result, we were able to create an ideal model. Now we can use this model to predict how many bikes will be rented each hour in order to keep the public's rental bike supply stable.

    On our training data, our r2 score for hyper parameter tuning using Grid Search CV on random forest regression was 94.95 % accuracy, while on our testing data, it was 86.25 % accuracy.
