# Foreign Exchnage Rate Forecasting

## Overview

This repository is a personal learning project where I explore Python for data science tasks, focusing on forecasting foreign exchange (FX) rates. Using the **US Dollar / Japanese Yen (USD/JPY)** exchange rate as the primary time series, combined with macroeconomic data from the US and Japan, I aim to understand the interplay between econometric and machine learning models in predicting FX prices.

## Objectives

1. **Learn and Practice Tools**:
   - Explore the functionality of **VSCode**, **Jupyter Notebook**, and **Python** for data science workflows.
2. **Data Exploration and Preparation**:
   - Start with reading and cleaning time series data.
   - Conduct descriptive statistical analysis.
3. **Forecasting Exchange Rates**:
   - Use econometric models (e.g., OLS, VAR) and machine learning models (e.g., XGBoost) to forecast FX rates.
   - Focus on precise predictions while visualizing results comprehensively.
4. **Visualization and Reporting**:
   - Create clear and informative visualizations (plots and tables) to present findings.

## Features

- **Data Handling**: Read and prepare time series data for modeling.
- **Descriptive Statistics**: Summarize key data features before analysis.
- **Model Implementation**: 
  - **Econometric Models**: Analyze trends, seasonality, and fundamental relationships.
  - **Machine Learning Models**: Experiment with algorithms like XGBoost to handle nonlinear patterns.
- **Visualization**: Plot time series trends, residuals, feature importance, and model performance.
- **Evaluation**: Use RMSE and other metrics to assess model accuracy.

## Key Takeaways

- Forecasting FX prices is inherently challenging due to:
  - The complex and dynamic nature of financial markets.
  - The interplay of numerous macroeconomic and geopolitical factors.
  - The presence of large prediction errors in models, regardless of the method used.
- Econometric models provide interpretability, while machine learning models excel in capturing nonlinear relationships. A combination of both approaches may yield the best results.

## Technologies Used

- **Python**: Core programming language.
- **Jupyter Notebook**: Interactive coding and visualization.
- **VSCode**: IDE for efficient development.
- **Libraries**:
  - **Data Handling**: `pandas`, `numpy`
  - **Visualization**: `matplotlib`, `seaborn`, `plotly`
  - **Modeling**: `statsmodels`, `xgboost`, `scikit-learn`

## Conclusion

Forecasting FX prices is a fascinating but difficult task. Both econometric and machine learning models provide valuable insights, yet they face limitations due to the unpredictability and complexity of FX markets. This project underscores the importance of combining technical rigor with practical considerations to derive actionable insights from FX forecasts.
