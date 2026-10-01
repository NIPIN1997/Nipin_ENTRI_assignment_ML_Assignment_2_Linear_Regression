# Regression
## Dataset
The California Housing Dataset available in the sklearn library is used.
## Preprocessing
1. The dataset is loaded into a dataframe.
2. The dataset is checked for duplicate rows.
3. The dataset is checked for missing values.
4. The skewness of the columns is corrected using logarithmic and square root transformations.
5. The dataset is scaled using StandardScaler.
## Training 
The regression algorithms used are:
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regressor
For each model the following parameters are calculated:
1. Mean Squared Error(MSE)
2. Mean Absolute Error(MAE)
3. R-Squared Score
## Conclusion
Random Forest Regressor have been identified as the best performing algorithm. Decision Tree Regressor and Linear Regression have been identified as the worst performing algorithms.