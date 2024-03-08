# Perrin Freres Monthly Time Series Analysis

## Project Overview

This Python project analyzes historical monthly sales data from the Perrin Freres champagne company, aiming to identify trends, seasonality, and create forecasts for future sales. The analysis employs time series techniques, including visualizations, statistical testing, and ARIMA/SARIMAX modeling.

## Key Steps

### Data Preparation

```
# Import necessary libraries
pip install pandas numpy statsmodels matplotlib

# Load the "perrin-freres-monthly.csv" dataset
import pandas as pd
import numpy as np
import statsmodels.api as sm
import matplotlib.pyplot as plt
%matplotlib inline

# Perform data cleaning tasks
# (code for renaming columns, handling missing values or outliers, converting "Month" to datetime, setting "Month" as index)
# Generate summary statistics
df.describe()

# Create a line plot of sales over time
df.plot()
plt.show()

# Conduct the Augmented Dickey-Fuller (ADF) test
# (code for ADF test)
# Apply differencing for stationarity
# (code for differencing, re-testing with ADF)
# ARIMA Model
# (code for experimenting with different ARIMA orders, creating ARIMA model, fitting, and reviewing)

# SARIMAX Model
# (code for incorporating seasonal ARIMA orders, creating SARIMAX model, fitting, and reviewing)
# In-sample forecasts
# (code for generating in-sample forecasts, plotting against actual sales)

# Out-of-sample forecasts
# (code for generating out-of-sample forecasts)

# Calculate forecast evaluation metrics
# (code for calculating MAE, RMSE)
# Plot original sales data alongside forecasts
# (code for plotting)

# Visualize model residuals
# (code for visualizing residuals)
