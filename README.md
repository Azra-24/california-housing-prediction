# Predictive Modeling of Housing Prices in California

This capstone project builds a regression-based machine learning model to predict median house prices across different California districts using demographic and geographic features. It is part of the Artificial Intelligence and Machine Learning course.

---

## Dataset Overview

- Source: `fetch_california_housing()` from scikit-learn
- Rows: 20,640
- Features: 8 input features
- Target: `MedHouseVal` – Median House Value

Key features used include:
- `MedInc`: Median income
- `HouseAge`: Average age of houses
- `AveRooms`: Average number of rooms
- `Latitude` and `Longitude`: Geographic coordinates

---

## EDA & Preprocessing

- No missing values in the dataset
- Dropped duplicate rows
- Scaled numerical features using `StandardScaler`
- Visualizations: heatmap, scatter plots, distribution plots

---

## Model Building

- Trained two models:  
  - Linear Regression  
  - Random Forest Regressor (selected as final model)
  
- Used `GridSearchCV` for hyperparameter tuning

---

## Evaluation Metrics

- R² Score: ~0.80
- MAE: [insert value]
- MSE: [insert value]
- Cross-Validation R²: ~0.78

---

## Project Files

- `California_Housing_ Pricesipynb.ipynb` – Complete Jupyter Notebook
- `cleaned_california_housing.csv` – Cleaned dataset
- `best_model.pkl` – Best estimator selected by GridSearchCV
- `final_model.pkl` – Final trained model saved for deployment or reuse
- `Capstone_Presentation.pdf` – Final project presentation (PDF format)

---

## Author

Shaik Azra Anisha  
AI & ML Capstone Project – 2025
