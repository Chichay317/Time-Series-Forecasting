# Time-Series-Forecasting

This project is a time series forecasting system that predicts gold prices based on historical monthly data. 
It applies exploratory data analysis (EDA), visualization, and multiple forecasting models to evaluate performance.

Features
1. Cleans and prepares the dataset with monthly gold prices from 1950–2020

2. Uses time-based indexing for proper resampling and analysis

3. Performs exploratory data analysis with boxplots, line plots, and resampled views (yearly, quarterly, decade)

4. Analyzes trend, seasonality, and volatility with coefficient of variation

5. Splits the dataset into training (before 2016) and testing (2016 onward)

6. Implements multiple forecasting models: Linear Regression, Naive Forecast, and Exponential Smoothing

7. Evaluates models using Mean Absolute Percentage Error (MAPE)

8. Visualizes forecasts alongside actual prices with 95% confidence intervals


How it Works

1. The dataset is prepared by creating a datetime index for monthly gold prices

2. Data is resampled to quarterly, yearly, and decade averages to highlight long-term patterns

3. Exploratory Data Analysis is performed with plots by year and month, and volatility is measured using coefficient of variation

4. Three forecasting models are applied: Linear Regression on time index, Naive Forecast (last observed value) and Exponential Smoothing (captures trend and seasonality)

5. Models are evaluated on the test set using MAPE

6. Final predictions are visualized with confidence intervals to account for uncertainty
