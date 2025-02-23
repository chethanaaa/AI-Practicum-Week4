In this experiment, I have employed grid search for hyperparameter tuning of an XGBoost model using the Weights and Biases (W&B) experiment tracking framework. Grid search systematically explores all possible combinations of hyperparameter values specified within predefined ranges. The hyperparameters considered include learning rate, max depth, subsample ratio, colsample by tree ratio, gamma and min child weight. I have defined a grid of parameter values for each hyperparameter and iterate through all combinations. For each combination, we train the XGBoost model using GPU acceleration and log the resulting root mean squared error (RMSE) metric to the W&B dashboard. By visualizing the RMSE values across different hyperparameter combinations, we can identify the optimal set of hyperparameters that minimizes the error and maximizes model performance.
