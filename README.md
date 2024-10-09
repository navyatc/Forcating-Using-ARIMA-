# Time Series Forecasting Using ARIMA and SARIMA

This project focuses on **Time Series Forecasting** using ARIMA and SARIMA models. It includes testing for stationarity, model selection, and prediction with real-world data. Both ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) are implemented for comprehensive forecasting.

## Project Overview

ARIMA and SARIMA are widely used statistical models for analyzing and forecasting time series data. This notebook includes:
- Testing for stationarity using the Augmented Dickey-Fuller (ADF) test.
- Model fitting using ARIMA and SARIMA models.
- Hyperparameter tuning with grid search.
- Rolling forecasting for model validation and residual diagnostics.

## Notebook Features

1. **Check for Stationarity (ADF Test) and Plot**:
   - Perform the Augmented Dickey-Fuller test to check the stationarity of the time series data.
   - Visualize the time series for analysis.

2. **Difference the Data and Plot**:
   - Apply differencing to the time series to make it stationary if necessary.

3. **Determine the Order of the ARIMA Model (ACF and PACF Plots)**:
   - Plot the ACF (AutoCorrelation Function) and PACF (Partial AutoCorrelation Function) to determine the order of the ARIMA model.

4. **Fit the ARIMA Model**:
   - Fit an ARIMA model to the time series data using the identified order.

5. **Make Predictions and Plot**:
   - Generate predictions using the fitted ARIMA model and visualize them.

6. **Seasonal Decomposition**:
   - Decompose the time series data to examine seasonal patterns using Seasonal Decomposition of Time Series (STL).

7. **Grid Search for ARIMA Hyperparameters**:
   - Perform grid search to find the best ARIMA model hyperparameters.

8. **Residual Diagnostics**:
   - Conduct residual analysis to evaluate model performance.

9. **Rolling Forecast Origin (Backtesting)**:
   - Use rolling forecast origin to validate the model on test data.

10. **Ensemble Methods**:
   - Explore ensemble techniques to improve model accuracy.

## Prerequisites

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `pmdarima`

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Navigate to the directory:
   ```bash
   cd your-repo-name
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebook:
   ```bash
   jupyter notebook ARIMA_SARIMA_TEST.ipynb
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
