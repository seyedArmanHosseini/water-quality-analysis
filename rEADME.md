# Water Quality Index Prediction

This project focuses on predicting the Water Quality Index (WQI) using real-world environmental and chemical parameters. The analysis applies supervised machine learning regression models to estimate the WQI based on given water sample features.

## Dataset Description

The dataset was obtained from [Kaggle]([https://www.kaggle.com/...](https://www.kaggle.com/code/seyedarmanhossaini/water-guality-index-wqi)), containing various measurements of water quality across chemical and physical indicators.

**Key features:**

- pH  
- Hardness  
- Solids  
- Chloramines  
- Sulfate  
- Conductivity  
- Organic_carbon  
- Trihalomethanes  
- Turbidity  
- Water Quality Index (WQI) [Target variable]

## Objective

To build a regression model that accurately predicts the **Water Quality Index (WQI)** using various chemical and physical properties of water samples.

## Models Used

- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor (best performing)  
- LightGBM Regressor (also tested)

## Methods

- Data Cleaning and Missing Value Imputation  
- Exploratory Data Analysis (EDA)  
- Feature Scaling  
- Model Training and Hyperparameter Tuning  
- Evaluation Metrics: MAE, RMSE, R² Score  
- SHAP Analysis for Interpretability

## Results

- XGBoost Regressor achieved the best performance.  
- Features like **Sulfate**, **Conductivity**, and **Organic Carbon** had the most influence on WQI predictions.

## Folder Structure

- `data/` – Contains raw and processed datasets.  
- `notebooks/` – Jupyter notebooks for EDA, modeling, and SHAP analysis.  
- `src/` – Source code including preprocessing, training, evaluation, and utility functions.  
- `README.md` – Project documentation.

## License

This project is open-source and available under the MIT License.

## Acknowledgments

Thanks to the original dataset contributors on Kaggle.


