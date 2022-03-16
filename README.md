# :bar_chart: :wavy_dash: :signal_strength: :vibration_mode: mobile_traffic_regression
Forecasting the volume of traffic at the base stations of a mobile operator using ML methods 

<img src='additionally/mobile_station.jpg' width ='250'/>

# Dataset info

* train.csv - the training set, shape (860750, 84)
* test-PUBLIC.csv - the test set, shape (261190, 41)

# Using:

* Data preprocessing
* Finding correlations
* Encoding categotical values
* Filling the missing values

* Models training: LinearRegression, RidgeCV, LassoCV, GradientBoostingRegressor, XGBRegressor

# Result

XGBRegressor showed the best results: train smape: 0.337, test smape: 0.335
