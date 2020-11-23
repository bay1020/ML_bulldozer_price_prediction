# bulldozer_price_prediction
# Predicting heart disease using machine learning

### 1. Problem definition

Predict the future sale price of a bulldozer by its characteristics and previous examples.

### 2. Data

Data from Kaggle.
Get more information of each features [here](https://www.kaggle.com/c/bluebook-for-bulldozers/data).

### 3. EDA

###### 1. Parsing dates

###### 2. Sort DataFrame by saledate

###### 3. Add datetime parameters for saledate column

### 4. Modeling
 
###### 1. Convert string to categories

###### 2. Fill missing numeric values with median

###### 3. Turn categorical variables into numbers and fill missing

###### 4. Fit and score model

###### 5. Hyerparameter tuning with RandomizedSearchCV

### 5. Evaluate

###### 1. Scores for model
|       |      Training     |       Valid       |
|-------|-------------------|:-----------------:|
| MAE   |2953.816113716348  |5951.247761444453  |
| RMSLE |0.14469006962371858|0.24524163989538328|
| R^2   |0.9588145522577225 |0.8818019502450094 |

### 6. Feature Importance
![feature_importance](https://github.com/bay1020/bulldozer_price_prediction/blob/main/features.png)
