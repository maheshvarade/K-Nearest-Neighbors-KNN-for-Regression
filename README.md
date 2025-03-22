K-Nearest Neighbors (KNN) for Regression using Auto MPG Dataset 🚗📊
This repository demonstrates K-Nearest Neighbors (KNN) Regression using the Auto MPG dataset. The dataset contains information about fuel efficiency (miles per gallon - MPG) based on features like horsepower, weight, acceleration, and displacement.

📌 Features & Workflow
Exploratory Data Analysis (EDA) 🔍

Data cleaning and handling missing values

Feature correlation using a heatmap

Feature Scaling ⚖

Applied StandardScaler for optimal KNN performance

KNN Regression Implementation 🤖

Used sklearn.neighbors.KNeighborsRegressor

Evaluated with MAE, MSE, RMSE, and R² score
Mean Squared Error is : 5.9066975
Root Mean Squared Error is : 2.430369827824564
Mean Absolute Error is : 1.8552499999999998
Accuarcy of knn model is : 89.01415625057032

Hyperparameter Tuning 🔧
 GridSearchCV
 Evaluated with  R² score
 Accuarcy of knn model is : 89.01415625057032
 
 RandomizedSearchCV to optimize n_neighbors
 Accuarcy of knn model is : 0.794548427975116


Improved accuracy with best k-value selection and  GridSearchCV has more accuaracy add less MAE
