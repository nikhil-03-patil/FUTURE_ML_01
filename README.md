# FUTURE_ML_01
📈 Sales Forecasting: Superstore Sales Prediction
Machine Learning Internship - Task 1
Objective: Predict future monthly sales based on historical data to assist in inventory planning and business decision-making.

📌 Project Overview
This project focuses on Time Series Forecasting using a real-world Superstore dataset. The goal is to predict the "Total Sales" for future months to help the business manager ensure sufficient inventory stock.
Using Linear Regression with engineered time-based features (Seasonality, Trends, and Lags), the model achieved an Error Rate of ~17.5%, providing a reliable baseline for monthly revenue estimation.

📊 Key Features & Methodology
Data Cleaning: Handled missing values and parsed complex date formats.
Feature Engineering: Created specific time-series features to capture patterns:
Seasonality: Extracted Month/Year to detect recurring annual spikes.
Lag Features: Used Lag_1 (Previous Month Sales) and Lag_12 (Same Month Last Year) to capture historical trends.
Modeling: Implemented Linear Regression to predict future sales.
Evaluation: Used MAE (Mean Absolute Error) and RMSE to quantify accuracy in dollar terms.


Business Insight:
Inventory Planning: The model accurately predicts end-of-year seasonal spikes. The business should increase stock levels by 15-20% in October to prepare for the predicted November/December surge.
Cash Flow: Finance teams can use the forecast to estimate incoming revenue with a known margin of error (~17%).


🖼️ Forecast Visualization
(Actual vs Predicted Sales for the final 6 months of testing)
<img width="1340" height="630" alt="image" src="https://github.com/user-attachments/assets/f501c6c4-8da0-4936-8847-c85f58672b10" />


🛠️ Tech Stack
Language: Python 3.10
Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
IDE: Jupyter Notebook




