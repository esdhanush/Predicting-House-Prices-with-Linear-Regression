# House Price Prediction

## Overview

This project focuses on predicting changes in house prices using machine learning techniques. By analyzing various economic indicators such as mortgage interest rates, rental vacancy rates, and consumer price index (CPI), combined with housing market data, the project aims to forecast future trends in house prices. The predictive model employed in this project utilizes a Random Forest Classifier to identify patterns and relationships between economic factors and changes in house prices.

## Data Sources

The project utilizes several datasets obtained from reputable sources:

- `CPIAUCSL.csv`: US Consumer Price Index (CPI)
- `RRVRUSQ156N.csv`: Quarterly rental vacancy rate
- `MORTGAGE30US.csv`: Weekly mortgage interest rates
- `Metro_median_sale_price_uc_sfrcondo_week.csv`: Median sale price for US houses
- `Metro_zhvi_uc_sfrcondo_tier_0.33_0.67_month.csv`: Zillow Home Value Index

## Methodology

1. **Data Collection:** The project starts by collecting and preprocessing economic indicators and housing market data.
2. **Feature Engineering:** Additional features are derived from the datasets to provide more insights into the relationships between economic factors and house prices.
3. **Model Training:** A Random Forest Classifier is trained on the preprocessed data to predict changes in house prices.
4. **Model Evaluation:** The performance of the model is evaluated using accuracy metrics and backtesting techniques to assess its effectiveness in predicting house price trends.
5. **Feature Importance Analysis:** Permutation importance is utilized to determine the significance of different economic indicators in predicting house price changes.

## Dependencies

- pandas
- scikit-learn
- matplotlib
