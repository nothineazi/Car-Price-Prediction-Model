# Car-Price-Prediction-Model
A machine learning model that predict car prices using Random Forest Regression. 
Trained on the selling data of a local car retailer.

We first find the correlations among the different features, and get the features importance.
Then we build our model, using a Random Forest Regressor so we don't need to scale our values since it uses decision trees.
Along with a Randomized Search CV (Cross-Validation) to tune the model, and speed up our training.
To evaluate the model, we use metrics such as MAE (Mean Absolute Error), MSE (Mean Squared Error) and RMSE (Root Mean Squared Error).
