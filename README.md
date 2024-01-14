# 統計學習初論期末專案檔案說明

- 我們這組使用Kaggle商品銷售數量預測比賽作為期末專案的題目，以下簡單說明各個檔案：

- notebook
    - EDA Time.ipynb  針對時間的特徵做EDA
    - EDA_snap.ipynb  針對特賣的特徵做EDA
    - Build Main DataFrame_Train.ipynb  將資料轉為方便分析的DataFrame
    - Model ARIMA regression.ipynb  以ARIMA模型學習
    - xgboost.ipynb  以XGBoost模型學習
    - DL_Models_用商品1作為例子.ipynb  以Deep Learning學習, 預測第一項產品
    - DL_ALL_Demo.ipynb  以Deep Learning學習, 預測完所有kaggle要求的項目
    - Prediction_combonation  輸出結果及在kaggle上的成績
    
- data
    - calendar.csv  日期、是否有特殊節日、
    - sales_train_evaluation 不同的商品與他們的類別、所在的州、分店、不同時間的銷售數量
    - sell_prices.csv  不同商品的價格
    
- submission.csv  最終各商品價格預測結果, 以此結果提交到kaggle