Perrin Frères Monthly Time Series Analysis
This project aims to analyze the monthly sales data of Perrin Frères, a fictional company, using Python and various libraries to understand the sales trends and predict future sales. The analysis involves data cleaning, exploratory data analysis (EDA), testing for stationarity, differencing, and applying an AutoRegressive Integrated Moving Average (ARIMA) model for forecasting.

Getting Started
Prerequisites
Python 3.x
Libraries: pandas, numpy, statsmodels, matplotlib
Installing
Clone the repository to your local machine and install the required libraries using pip:

pip install pandas numpy statsmodels matplotlib
Running the Analysis
Ensure you have the perrin-freres-monthly.csv dataset in the same directory as your Python script.
Run the Python script in a Jupyter Notebook or any Python environment.
Project Overview
Data Cleaning
The dataset is loaded into a pandas DataFrame.
The last two rows are dropped as they contain incomplete data.
The 'Month' column is converted to a datetime format and set as the DataFrame index.
Exploratory Data Analysis (EDA)
Basic statistical analysis is performed using the describe() method.
The sales data is visualized to understand the trend and seasonality.
Stationarity Test
The Dickey-Fuller test is applied to check if the time series data is stationary.
If the data is non-stationary, differencing is applied to make it stationary.
AutoRegressive Model
An ARIMA model is fitted to the data to forecast future sales.
The model is evaluated and used to predict sales for the next 24 months.
Results
The analysis provides insights into the sales trends of Perrin Frères and forecasts future sales using an ARIMA model. The forecasted sales are visualized along with the actual sales data.

Conclusion
This project demonstrates the application of time series analysis techniques to understand and predict sales trends. The ARIMA model provides a robust framework for forecasting, which can be further improved by incorporating additional features or using more advanced models.

Contributing
Contributions are welcome. Please feel free to fork the repository and create a pull request with your changes.
