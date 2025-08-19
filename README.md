# SuperShop Sales Prediction ML Project

## Overview
The SuperShop Sales Prediction project aims to forecast sales for products in different supermarket outlets using historical sales data. The project uses machine learning (XGBoost regression) to predict future sales, helping supermarkets manage inventory, plan pricing, and make informed business decisions.


## Features
- Predict sales for different products and outlets.
- Handle missing data and clean the dataset automatically.
- Encode categorical features for machine learning models.
- Perform exploratory data analysis to identify trends and patterns.
- Train and evaluate XGBoost regression model for accurate predictions.



## Implementation
1. Load dataset using `pandas`.
2. Handle missing values in `Item_Weight` and `Outlet_Size`.
3. Perform exploratory data analysis using `matplotlib` and `seaborn`.
4. Encode categorical features using `LabelEncoder`.
5. Split dataset into features (`X`) and target (`Y` = `Item_Outlet_Sales`).
6. Train-test split (80%-20%) using `train_test_split`.
7. Train XGBoost regression model.
8. Evaluate model performance using R² score.

## Environment
- **Python**: 3.13.5
- **Platform**: Google Colab  
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`  

## Results
- Training R² score: 0.876  
- Test R² score: 0.502  

The model captures patterns in product and outlet features and helps supermarkets forecast sales for better inventory and business decisions.



#Dsataset
1. Kaggle Dataset: [Supermarket Sales Dataset](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data)  





