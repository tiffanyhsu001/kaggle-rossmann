# Rossmann Stores Sales Prediction

In this Kaggle case study: 
I was provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set.
This repo includes exploratory analysis and predictive modeling.

**OBJECTIVE**
Forecast Sales in Rossmann stores using historical data.

**METHODOLOGY**
- First begin with extensive exploratory analysis to find kinks in the data, ie recognize outliers, invalid data points, missing data points. Perform some data mining/wrangling to explore features that can be used in feature engineering.
- Build the model:
    - Train Test Split: for validation purposes and check success of the model
    - Random Forest Model: chosen for its speed, robustness against outliers & overfitting
    - Extreme Gradient Boosting Model: chosen for its strong large tree scale boosting ability

**CONCLUSION**
My XGB model performed slightly better than my random forest model. However, due to XGB's much longer performance, I would recommend running a random forest model since they had relatively similar scores. Further improvements to the models would include hyperparameter tuning, as I only extracted variables based off feature importances.
  
