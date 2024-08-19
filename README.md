# Store Sales - Time Series Forecasting
.

## About the project

專案目標是預測厄瓜多 Favorita 超市的銷售金額。資料期間為2013 年 1 月 1 號到 2017 年 8 月 15日

這個專案主要分為兩個部分：Orginal Dataset與Aggregated Dataset
Orginal Dataset: 每一個時間點有多筆資料（不同商品類別、分店），這部份我們用一般的模型進行預測。
Aggregated Dataset：將Original Dataset不同商品類別、分店的銷售金額加總，所以每個時機點只有一筆數據，這部分我們用時間序列模型進行預測。


資料集來源 [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)

Python notebook在 Forecasting.ipynb 這個檔案裡

## Built with

- Python 3.10.12
- Jupyter Notebook
