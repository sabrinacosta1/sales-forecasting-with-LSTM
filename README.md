# sales-forecasting-with-LSTM
## Overview
This project is a complete end-to-end pipeline for sales forecasting using **Long Short-Term Memory (LSTM)**, a type of Recurrent Neural Network (RNN). The system leverages historical sales data to forecast the **demand for spare parts over the next 12 months**, enabling businesses to make data-driven decisions in inventory management and production planning.

## Objective
1. **Data Cleaning & Structuring**: Preprocess historical sales data to remove outliers, fill missing values, and format it for analysis.
2. **Time Series Analysis**: Analyze seasonal trends and patterns in the data.
3. **LSTM Model Training**: Train an LSTM model to predict future sales demand, leveraging its ability to capture long-term dependencies in time series data.
4. **Forecast Future Demand**: Generate 12-month demand predictions for all materials, aiding in **strategic decision-making**.

## Features
- **Data Preprocessing**:
  - Outlier removal using Interquartile Range (IQR) and replacement with mean values.
  - Creation of time-based features for yearly and monthly aggregation.
  - Normalization and pivoting of sales data for model compatibility.
- **Exploratory Data Analysis (EDA)**:
  - Visualization of yearly sales trends and monthly sales heatmaps.
- **LSTM Model Architecture**:
  - Four-layer LSTM network with dropout for regularization.
  - Early stopping to prevent overfitting and optimize training time.
- **Evaluation Metrics**:
  - Root Mean Squared Error (RMSE)
  - Coefficient of Determination (R²)
  - Mean Absolute Percentage Error (MAPE)
- **Results Export**:
  - Forecast results for each material exported to Excel for further analysis.

## Key Visualizations
1. **Yearly Sales Trends**: Highlights annual growth and demand patterns.
2. **Monthly Sales Heatmap**: Visualizes seasonal patterns across multiple years.
3. **Forecast vs. Actual**: Compare predicted demand against actual values for individual materials.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sabrinacosta1/sales-forecasting-with-LSTM.git
   cd sales-forecasting-with-LSTM

## Usage
Run the Script

The script will:
Preprocess the data.
Train the LSTM model.
Evaluate the model and export results.

Outputs are saved in the outputs folder:
Forecasted values for all materials.
Evaluation metrics summary.
