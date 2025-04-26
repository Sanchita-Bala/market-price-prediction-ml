# consignment market-price-prediction using machine learning

## Overview:
Using variables from existing datasets, this project mainly aims to develop a predictive model that forecasts consignment prices.Forecasting the Line Item Insurance (USD) value from a logistics dataset is the goal of this project. Its clean, modular, testable, and easily maintainable.Python codebase is achieved through the use of standard machine learning techniques. Also offered is an interactive Streamlit dashboard for real-time prediction.

## Project workflow:
1."Load dataset"
2."Data cleaning and feature engineering"
3."Train ML model"-using RandomForestRegressor, linear regressor
4."Evaluate Model"
5."Streamlit Dashboard"-for live prediction

## Requirements of python libraries
pandas,scikit-learn,seaborn,streamlit,numpy,matplotlib

## Model selection
The Random Forest model is the best fit for this provided dataset after trying out a variety of regression models such as Linear Regression, Decision Tree, Random Forest, Gradient Boost, etc. are tried out. The model works equally well on the training and test sets with excellent R-squared values and comparatively low errors (MSE, RMSE, MAE). Compared to some other models, the Random Forest model will be less susceptible to overfitting because it finds a balance between being complex and being able to generalize.

## Among the dataset,three factors have given more priority for logistics prediction:
1.Line Item Insurance
2.Freight cost
3.Line Item Quantity

## Outputs:
Prediction Line Item Insurance (USD)

## Conclusion:
This project shows how machine learning can help to predict consignment prices in logistics.