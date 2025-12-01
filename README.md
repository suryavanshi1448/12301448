# Car Price Prediction – CarDekho 50K Dataset

**Student:** Abhishek Suryavanshi  
**Reg. No.:** 12301448  
**Program:** B.Tech CSE, DAV University

## Overview
A machine learning project aimed at predicting car prices using the CarDekho 50K dataset.  
Three regression models were implemented: Linear Regression, Random Forest, and XGBoost.

## Dataset
- File: `data/cardekho_style_cars_50k.csv`
- Source: Kaggle  
- Includes 50,000 car listings with specifications and price details.

## Model Results
**Train/Test Split:** 80/20  
**Target:** `price`

| Model             | R²    | RMSE  |
|-------------------|-------|-------|
| Linear Regression | 0.792 | 28329 |
| Random Forest     | 0.784 | 28895 |
| XGBoost           | 0.786 | 28776 |

## Outputs
- `car_cleaned_50k.csv`  
- `linear_model.pkl`  
- `rf_model.pkl`  
- `xgb_model.pkl`  

## How to Run
1. Place the dataset (car_cleaned_50k.csv) inside `data/`.  
2. Open `final12301448.ipynb` in Google Colab.  
3. Run all cells to train models and generate outputs.

## Acknowledgements
- Kaggle (dataset)  
- AppTechies Company (guidance)
