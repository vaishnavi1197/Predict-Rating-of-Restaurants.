# Predict-Rating-of-Restaurants.

You can find the dataset as .xlsx file or download it from kaggle. 

This is a Regression problem. In an overview, I started with **DATA CLEANING and DATA PROCESSING. Then ExtraTreesRegressor was used to EXTRACT important FEATURES. After data was ready for the model, to predict ratings, I started off with the most basic regression model which is LINEAR REGRESSION. Analyzing the need for improvement in predictions from linear regression, I decided to build an unsupervised learning model before the supervised learning model. So, K MEANS CLUSTERING was built before LINEAR REGRESSION. Now, for a test point, linear regression was performed only within its identified cluster given my kmeans. This improved the performance of linear regression. In the end RANDOM FOREST REGRESSION model was also built on the data to compare the performance of ENSEMBLE SYSTEM on this data set.
