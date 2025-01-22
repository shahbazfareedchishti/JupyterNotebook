I used following methodology to work on Boston Housing Dataset:
1. Detected Missing values
2. Checked if missing values are correlated
3. Used correlation matrix to check which features are closely related to MEDV
4. Handled outliers in the dataset by using KNNImputation because data was not normally distributed
5. Then I applied LinearRegression model
6. Predictions were made at the end
Accuracy of this model is 72% because majority of the features have non linear relationship with MEDV, only RM and LSTAT are correlated to MEDV, where RM is positively correlated and LSTAT is negatively correlated. achieving 80% accuracy by using LinearRegression model on BostonHousing dataset is uncommon.
