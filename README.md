# Kaggle - M5 Forecasting Accuracy

- This is my final group project in the Statistical Learning course in college. I teammed with other 3 people to build a forecasting model for the Kaggle competition - M5 Forecasting - Accuracy. The goal is to predict sales quantity of products. Please refer to the link for more details.
https://www.kaggle.com/competitions/m5-forecasting-accuracy

- Here is a brief explanation of each file.

- Notebook:
    - EDA Time.ipynb: Exploratory Data Analysis (EDA) on time-related features
    - EDA_snap.ipynb: EDA  on features related to special sales (SNAP)
    - Build Main DataFrame_Train.ipynb: Converts the data into a DataFrame suitable for analysis
    - Model ARIMA regression.ipynb: train in ARIMA model
    - xgboost.ipynb: train in XGBoost model
    - DL_Models_1st_product_example.ipynb: train in Deep learning model to predict the first product
    - DL_ALL_Demo.ipynb: train in Deep learning for predicting all the items requested by Kaggle.
    - Prediction_combination: Outputs the results and Kaggle scores.
- Data:
    - calendar.csv: Contains dates and information about special holidays.
    - sales_train_evaluation: Sales quantity of different products, their categories, locations (state and store), and time.
    - sell_prices.csv: Prices of different products.
    - submission.csv: Final predictions of prices for each product, submitted to Kaggle.
