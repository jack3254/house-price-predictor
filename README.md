# 🏡 房價預測系統（House Price Predictor）

[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Model](https://img.shields.io/badge/Model-LinearRegression%20%7C%20XGBoost-orange)]()

本專案使用 Python 與機器學習模型，預測房屋銷售價格。使用 Kaggle 的房價資料集（House Prices - Advanced Regression Techniques）。

## 🔧 功能
- 使用 Linear Regression、Random Forest、XGBoost 建立模型
- 特徵工程：處理缺失值與類別資料
- 預測模型儲存 (`joblib`)
- 可視化殘差圖與預測效果
- 評估指標：RMSE、R²

## 🚀 執行方式
```bash
pip install -r requirements.txt
jupyter notebook notebook/house_price_model.ipynb

