# Dominos: Sales Forecasting and Purchase Order Optimization

## Overview
This project focuses on developing a predictive model to optimize Dominos’ ingredient ordering process by forecasting future sales. The goal is to predict weekly sales accurately and generate an efficient purchase order for ingredients, minimizing waste, avoiding stockouts, and streamlining the inventory management process.

Leveraging time series forecasting models such as ARIMA, SARIMA, Prophet, and XGBoost, I achieved a Mean Absolute Percentage Error (MAPE) of 0.30. This allowed for accurate sales predictions and the successful forecasting of the quantity needed for the next week.

## Skills Gained
Through this project, I gained experience in:

- **Data Preprocessing and Cleaning:** Removing missing or inconsistent data, handling outliers, and formatting data for analysis.
- **Exploratory Data Analysis (EDA):** Identifying sales trends, seasonality, and other patterns in historical sales data through visualization and analysis.
- **Feature Engineering:** Creating relevant features such as day of the week, month, promotional periods, and holiday effects.
- **Time Series Forecasting Models:** Implementing models like ARIMA, SARIMA, Prophet, and XGBoost for accurate sales prediction.
- **Model Evaluation:** Using MAPE to assess and compare the performance of different models.
- **Inventory Management:** Applying sales forecasts to calculate the required quantities of ingredients and generate a purchase order.
- **Supply Chain Optimization:** Streamlining the ingredient ordering process to align with predicted sales, reducing disruptions.

## Project Problem Statement
### Objective
The primary objective was to develop a robust predictive model capable of forecasting weekly pizza sales and generating a purchase order to ensure Dominos maintains optimal stock levels. The forecast helps avoid overstocking, reduce waste, and minimize the risk of stockouts.

### Project Scope
The dataset used for this project contains historical sales data and ingredient information. The project includes:

1. **Data Preprocessing and Exploration:**
   - Cleaning data by handling missing entries, outliers, and ensuring consistent formatting.
   - Conducting Exploratory Data Analysis (EDA) to uncover trends, seasonality, and patterns in the sales data.

2. **Model Development:**
   - Implementing time series forecasting models including ARIMA, SARIMA, Prophet, and XGBoost to predict pizza sales.
   - Engineering relevant features such as day of the week, holiday effects,Months to improve model accuracy.
   - Evaluating the models using MAPE to determine which approach performs best.

3. **Sales Forecasting and Purchase Order Generation:**
   - Predicting pizza sales for the next week using the chosen model.
   - Calculating the necessary quantities of each ingredient based on forecasted sales and ingredient consumption rates.
   - Generating a detailed purchase order that specifies the quantities of ingredients required for the upcoming week.

### Key Features
- **Accurate Sales Forecasting:** Time series models such as ARIMA, SARIMA, Prophet, and XGBoost achieved a MAPE score of 0.30, providing highly accurate sales predictions.
- **Efficient Inventory Management:** The sales forecast informs ingredient ordering, reducing waste and preventing stockouts.
- **Supply Chain Optimization:** The predictive model streamlines the ordering process and minimizes disruptions, enhancing operational efficiency.

## Results
- Achieved a MAPE score of **0.30**, ensuring accurate sales forecasting.
- Successfully forecasted the quantity of ingredients required for the next week, optimizing Dominos' purchase order process.

## Conclusion
This project highlights how time series forecasting can optimize inventory management and sales forecasting in the food industry. By accurately predicting sales and generating a purchase order, Dominos can improve efficiency, reduce waste, and ensure smooth operations. The model’s high accuracy provides a reliable foundation for future improvements in supply chain and inventory management.
