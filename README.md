# Water Demand Forecasting using LSTM and Gradient Boosting
A hybrid machine learning project that forecasts short-term water demand using historical water consumption data. The model combines Long Short-Term Memory (LSTM) networks and Gradient Boosting Regression to capture temporal patterns and non-linear relationships in water consumption.

## Overview
- **LSTM:** Captures sequential patterns and long-term dependencies in historical water consumption data.
- **Gradient Boosting:** Models non-linear relationships using engineered features such as seasonal patterns, academic periods, and day types.
- **Hybrid Model:** Combines LSTM and Gradient Boosting predictions using an RMSE-based weighted averaging approach to generate more reliable water demand forecasts.

## Approach
1. **Data Preprocessing:** Prepared and cleaned historical water consumption data using Pandas and NumPy.
2. **Feature Engineering:** Incorporated seasonal variations (Summer, Winter, Rainy), academic periods, and day-type information to improve prediction accuracy.
3. **Model Development:** Trained an LSTM network and Gradient Boosting Regressor to learn temporal and non-linear consumption patterns.
4. **Hybrid Integration:** Combined predictions from both models using RMSE-based weighting.
5. **Model Evaluation:** Used an 80:20 chronological train-test split to evaluate forecasting performance on unseen data.
6. **Demand Forecasting:** Generated date-based forecasts for the next 7 days and visualized predicted water consumption in litres.

## Results
- Achieved an **R² score of 0.959** with the hybrid forecasting model.
- Evaluated model performance using RMSE, MAE, and MAPE.
- Developed a 7-day forecasting approach to estimate future water consumption.
- Visualized predicted water demand to support short-term consumption planning.

## Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, scikit-learn
- **Deep Learning:** TensorFlow / Keras
- **Models:** Long Short-Term Memory (LSTM), Gradient Boosting Regressor
- **Techniques:** Time-Series Forecasting, Feature Engineering, Hybrid Machine Learning, Data Visualization

## Author
**Kiruthika S**

[LinkedIn](https://linkedin.com/in/kiruthika-s-d73/) | kiruthika.0735@gmail.com
