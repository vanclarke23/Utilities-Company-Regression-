# Utilities-Company-Regression-
# AFM 244 – Week 10 Assignment

## Overview
This notebook develops and evaluates regression models to predict revenue using production and weather-related variables. Several models are compared to determine which provides the most accurate predictions.

## Contents
- Data preparation and exploration
- Simple linear regression models:
  - Revenue vs. Production
  - Revenue vs. Cooling Degree Days (coolDD)
  - Revenue vs. Heating Degree Days (heatDD)
- Multiple linear regression models
- Model evaluation using MAPE
- Final model selection
- Visualization comparing actual and predicted revenue

## Final Model
The selected model uses:
- **Production**
- **Heating Degree Days (heatDD)**

This model was chosen because it achieved the lowest Mean Absolute Percentage Error (MAPE) compared to the other models, indicating the best predictive performance.

## Tools Used
- Python
- pandas
- NumPy
- matplotlib
- scikit-learn

## Files
- `AFM244_S26_Week10_Tuesday.ipynb` – Complete analysis, model development, and visualizations.

## Author
Vanessa Clarke
