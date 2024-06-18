![Screenshot 2024-06-14 193958](https://github.com/akesh-0909/Sales-Analysis-and-forecasting/assets/155313882/43768a64-0c60-443f-b28b-f15f57e5f400)


# 📊 Sales Forecasting for XYZ Drug Stores

Welcome to the Sales Forecasting project for XYZ Drug Stores! This repository contains the code and Analysis ppt for forecasting sales of 1115 drug stores using historical sales data and advanced machine learning techniques.


## 📋 Project Overview

XYZ Drug Stores operates over 3000 drug stores across 7 countries. Store managers need to predict daily sales up to six weeks in advance, which are influenced by promotions, competition, holidays, seasonality, and locality.

## 🔍 Problem Statement

The objective of this project is to forecast the "Sales" column for the test set, using historical sales data from 1115 XYZ Drug Stores. Some stores were temporarily closed for refurbishment, and those entries have been handled accordingly.

## 📁 Data Overview

- Data is taken from remote repository
  
- **sales.csv**: Contains the sales data for all stores.  [URL](https://drive.google.com/uc?id=1b9T0ZLpoITsb1A4u69-ykl6T5Skct4ER) <br>
- **store.csv**: Contains information about 1115 stores. [URL](https://drive.google.com/uc?id=1EaEpVwZdl3K-AzQljWQFfyUaazxV7l2Z)

- **Train Set**: Data from 2013-01-01 to 2014-12-31.
- **Test Set**: Data from 2015-01-01 to 2015-07-31.

## 📈 Model Selection and Evaluation

Given the large dataset and the nature of the sales data, we employed the following techniques:
- **Linear Hypothesis**: if Sales have linear relationships with features we apply Stochastic Gradient Descent.
- **Non-Linear Hypothesis**: if Sales have non-linear relationships with features we apply Xgboost Regressor or deep learning.

### 🚀 Performance Metrics

- **Training Error**: 726.666
- **Testing Error**: 886.539
- **Cross Validation Score**: 810.57

## 🔧 Features Analysis

Key features analyzed include:
- **Sales and Store Status**: Sales are log-normally distributed with many zero values due to store closures and holidays.
- **Store Type**: Different store types show varying sales patterns, with type 'B' performing notably well.
- **Promotions**: Promotions generally boost sales, but their effect varies across store types.
- **Competition**: Competitor presence impacts sales, with older competitors posing a greater challenge.

## 📊 Feature Importance

The most important features identified are:
- **Customers**
- **First Promotional Activities**

## 🌟 Conclusion

This project successfully developed a robust model to forecast sales, providing valuable insights for inventory management, staffing, and marketing strategies. The use of XGBoost Regressor, supported by GPU operations, ensured efficient handling of the large dataset.


## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

For any inquiries, please contact:
- **Akesh Kumar**
- [Email](mailto:akeshkumar65885@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/akesh-kumar/)
- [GitHub](https://github.com/akesh-0909)

Thank you for your interest in this project! 🙌

