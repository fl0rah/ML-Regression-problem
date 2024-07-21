Dataset from kaggle(https://www.kaggle.com/competitions/autoam-car-price-prediction)
The purpose is to guess the price of a car using its characteristics. Not all characteristics can be used when predicting the price. Make predictions using machine learning algorithms or deep learning networks.
- train.csv - training set
- test.csv - test set for price predicting
- sample_submission.csv - sample of submission file
- sub.csv - predicted file
For the first I analysis data, make text to digits
For model I use LinearRegression, RandomForestRegressor, AdaBoostRegressor, GradientBoostingRegressor, DecisionTreeRegressor, PolynomialFeatures, SVR
And finally I use GridSearchCV for finall model(the model that is good for my dataset).
