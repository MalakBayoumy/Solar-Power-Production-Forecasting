# Solar Power Forecasting  
🏆 **1st Place Winner** – SAS Hackathon for Sustainability & Data4Good

## Project Summary

This project focuses on forecasting solar power generation using a combination of statistical and machine learning-based time series models. Developed during the SAS Hackathon as a collaborative team effort, the project secured **1st place** for its innovative and impactful application of data science to sustainability challenges.

## Objective

The goal of this project is to compare traditional statistical forecasting models with modern machine learning approaches. We evaluated their performance under various preprocessing workflows and forecasting strategies, using solar energy production data as a structured time series problem.

## Forecasting Approaches

We explored and implemented three main forecasting strategies:

- **Direct Forecasting:** Predicting future values independently for each time step.
- **Recursive Forecasting:** Using previous predictions as inputs to forecast future values.
- **Hybrid Approach:** A combination of direct and recursive techniques.

## Models Applied

### Statistical Models
- **Auto ARIMA**
- **Auto ETS**

### Machine Learning Models
- **LightGBM**
- **Linear Regression**
- **LSTM (Long Short-Term Memory Neural Networks)**

## Key Insights

- **LightGBM** delivered the best performance based on **Mean Absolute Error (MAE)**.
- **Linear Regression** achieved the lowest **Mean Squared Error (MSE)**.
- The **Recursive Forecasting Strategy** demonstrated the most reliable and consistent results across different setups.

