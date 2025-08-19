# Advanced Feature Engineering for House Prices Prediction

This repository contains my journey through the Kaggle House Prices competition, focusing on advanced feature engineering techniques to improve prediction accuracy.

## Competition
[House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Progress

### Day 1: Baseline Model
- Basic data cleaning and preprocessing
- Simple feature engineering (TotalSF, TotalBath, TotalPorchSF)
- Lasso + XGBoost + LightGBM ensemble
- **Score: [Your Day 1 Score]**

### Day 2: Advanced Feature Engineering (Current)
- Quality × Area interaction features (OverallQual_TotalSF, etc.)
- Sophisticated aggregate features (TotalSquareFootage, TotalOutsideSF)
- Neighborhood-based average pricing
- Bathroom and room efficiency ratios
- **Score: [Your Day 2 Score]**

## Project Structure
advanced-feature-engineering/
├── data/ # Raw and processed data
├── notebooks/ # Jupyter notebooks
├── src/ # Python source code
├── models/ # Saved models
└── submissions/ # Kaggle submission files

## How to Run
1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Run notebooks in sequence: `01_eda_and_baseline.ipynb` → `02_advanced_feature_engineering.ipynb`

