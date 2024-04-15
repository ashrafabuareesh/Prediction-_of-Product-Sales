![Forecast](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/376f26ba-0199-412d-a2ac-90fc8385ced9)



# Prediction of Product Sales
 - Ashraf Abu Areesh

Forecasting sales of food items sold in different stores. The goal is to help the retailer understand which product and outlet characteristics play critical roles in increasing sales.

 # Data Source:
  - Big Mart Sales Prediction : https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/
  - For this dataset, there were 8523 rows and 12 columns.
 # Data Dictionary:
  ![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/9f1844bd-12bd-4884-a931-84bde2754ed0)

 # To prepare this data, the data was cleaned, and the following processes were performed:

 ## Exploratory Data Analysis
   * the graph shows average sales in stores

![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/c33012b3-b386-44bf-94ee-2ce28a35891f)
 
 ## Exploratory Data Analysis
 ![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/8bcaf6a0-9d54-4c3d-93e6-417b11ce001c)
* By carefully examining the graph showing items sold in each store, you can gain valuable insights into store performance, customer preferences, and potential areas for optimization or intervention.
* The highest average seles of all items in a supermarket type3
* The lowest average seles of all items in a grocery store
 ## Exploratory Data Analysis
![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/154ec1ab-6143-49e9-a2c4-1f455c661885)
![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/0698222e-46f0-402c-8e01-42a26d3d7cb5)
* By carefully examining the graph showing items sold in each store, you can gain valuable insights into store performance, customer preferences, and potential areas for optimization or intervention.
* You might notice that certain stores sell more items than others, indicating differences in popularity, location, or marketing effectiveness.
* Older stores might have had more time to establish their brand and reputation within the community, leading to higher sales due to customer loyalty and trust.
* Older stores might be located in more favorable or established areas with higher foot traffic ,leading to higher sales.

# Maching Learning Using the Following Models:
  - Linear Regression Model
  - Random Forest Regressor Model
  - Tuned Random Forest Regressor Model
    
# Models Evaluated & Results
- Linear Regression Model (Testing Set):

    - R^2: 0.567
    - MAE: 804.194
    - MSE: 1194694.512
    - RMSE: 1093.021
  ## Your LinearRegression coefficients plot
     ![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/27daf91b-204a-4e1d-99e3-e781e8d428f0)

 *  outlet type : The type of store (outlet type) can be a factor that greatly influences sales and business performance for the reasons: Shopping Experience: All kinds of products we offer for a different shopping experience.
 *  item_MRP : The maximum selling price of the item also seems to be important, as this factor usually reflects the value of the product and its demand by customers.
 *   item_type_seafood : The presence of seafood in a store can have a significant impact on store performance and sales for several reasons:
       -  Increase in additional sales
       - Healthy options
       - Uniqueness and distinction


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
  ##  the feature importances (Random Forest Regressor) :
    ![image](https://github.com/ashrafabuareesh/Prediction-_of-Product-Sales/assets/123064338/92521c4d-e448-4127-bc12-284dd598950d)
  * the top 5 most important features:
     - item_MRP : The maximum selling price of the tourist item is one of the most important factors that determine revenue and profitability
     - outlet type : The type of store can greatly affect the level of sales, as stores with larger sizes and popularity can attract more customers and thus increase sales.
     -  item visibility : Product visibility refers to how clearly the product appears in the store. The more visible the product is, the greater the chance that customers will buy it.
     - item_weigt:  The weight of the product can affect several aspects such as shipping cost, storage costs and sales.
     - outlet_Establishment _year : The year a store was founded can affect the level of sales
* These five characteristics are very influential in analyzing data, guiding marketing strategies, and making managerial decisions in the context of merchandising and retailing.

- The Final Model Chosen was a Random Forest Regressor Model with the n_estimators tuned to 150.
- For the testing set on the model, 59.2% of the variance in y was explained by x.
- The Mean Absolute Error was off by about $738.078.
- The Root Mean Squared Error had a calculation of $1,061.272.
- The Mean Absolute Error was off by about $738.078.

 Overall, these metrics provide insights into the performance of the tuned Random Forest Regressor model. An R^2 of 0.592 suggests that the model explains a moderate amount of the variability in sales prices, while the MAE, MSE, and RMSE provide measures of the average errors made by the model in predicting sales prices.


# Recommendations : 
 - Feature Engineering: Explore additional features or transform existing features to better capture the underlying patterns in the data.
 - Additional Data: Consider gathering additional relevant data that may further enhance the model's predictive power.
 - Model Evaluation: Continuously monitor and evaluate the model's performance on new data and iterate on improvements as needed. Regularly updating and retraining the model with fresh data can help ensure its relevance and effectiveness over time.

# For Further Information: 
- aashrafareesh1998@gmail.com

