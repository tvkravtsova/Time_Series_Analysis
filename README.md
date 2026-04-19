# Time Series Analysis

This project contains a time series analysis workflow implemented in a Jupyter Notebook.
The notebook includes deep exploratory analysis, seasonality checks, feature engineering, multiple forecasting experiments, and rolling backtest validation for model selection.

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
- Forecasting experiments across classical ML, and deep-learning approaches:
  `XGBoost` (with time covariates via `darts`), `ExponentialSmoothing`, `ARIMA`, `SARIMAX` (with exogenous features), `Prophet`, and `LSTM`
- Multiple experiment iterations with different preprocessing, scaling, feature sets, and model configurations
- Robust model validation with rolling (walk-forward) backtest to compare candidates and identify the best-performing approach
- Detailed evaluation with forecasting error metrics (including `MAPE`) and side-by-side prediction vs actual visualizations

## Requirements

Use Python 3.9+ (recommended) and install dependencies:

```bash
pip install -r requirements.txt
```

Depending on your environment, `darts` may require additional backend dependencies.

## Outputs

The notebook produces:

- Visual diagnostics of trend and seasonality
- Decomposition plots
- Forecast plots vs actual values for multiple model families
- Backtest diagnostics for model comparison
- Error metrics for model performance across experiments

