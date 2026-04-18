# Time Series Analysis

This project contains a practical time series analysis workflow implemented in a Jupyter Notebook.
The notebook covers data preparation, exploratory analysis, seasonality checks, decomposition, feature engineering, and forecasting with machine learning models.

## Project Structure

- `Time_Series_Analysis.ipynb` - Main notebook with the full analysis and modeling pipeline.

## What Is Included

- Data loading and initial preprocessing
- Datetime conversion and index setup
- Exploratory visual analysis of trends and product-level behavior
- Correlation analysis and confidence-interval visualizations
- Time series decomposition
- Autocorrelation/partial autocorrelation and seasonality checks
- Feature engineering based on date/time components
- Forecasting with `darts` and `XGBoost`
- Model evaluation and visualization of predictions

## Requirements

Use Python 3.9+ (recommended) and install the main dependencies:

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn statsmodels xgboost darts
```

Depending on your environment, `darts` may require additional backend dependencies.

## Outputs

The notebook produces:

- Visual diagnostics of trend and seasonality
- Decomposition plots
- Forecast plots vs actual values
- Error metrics for model performance

