# Prediction of-Product-Sales
Forecasting sales of food items sold in different stores. The goal is to help the retailer understand which product and outlet characteristics play critical roles in increasing sales.

 * the graph shows average sales in stores

![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/c33012b3-b386-44bf-94ee-2ce28a35891f)

* You might notice that certain stores sell more items than others, indicating differences in popularity, location, or marketing effectiveness.
![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/154ec1ab-6143-49e9-a2c4-1f455c661885)
* Older stores might have had more time to establish their brand and reputation within the community, leading to higher sales due to customer loyalty and trust.
* Older stores might be located in more favorable or established areas with higher foot traffic ,leading to higher sales.
![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/0698222e-46f0-402c-8e01-42a26d3d7cb5)

## Models Evaluated & Results
- Linear Regression Model (Testing Set):

    - R^2: 0.567
    - MAE: 804.194
    - MSE: 1194694.512
    - RMSE: 1093.021

- Random Forest Regressor Model (Testing Set):

  - R^2: 0.562
  - MAE: 763.239
  - MSE: 1209292.343
  -  RMSE: 1099.678
- Tuned Random Forest Regressor Model (Testing Set):

   - R^2: 0.592
   - MAE: 738.078
   - MSE: 1,126,298.846
   - RMSE: 1,061.272

- The Final Model Chosen was a Random Forest Regressor Model with the n_estimators tuned to 150.
   - The Mean Absolute Error was off by about $738.078.
   - The Root Mean Squared Error had a calculation of $1,061.272.

