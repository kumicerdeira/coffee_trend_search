# coffee_trend_search
Project Overview This project uses the Google Trends API (pytrends) to collect and analyze coffee-related trend data from Japan and Spain. The collected data is visualized using matplotlib. Additionally, an ARIMA (AutoRegressive Integrated Moving Average) model is applied to forecast future trends.

 To evaluate the predictive model, the following metrics were used:

MAE (Mean Absolute Error): Measures the average of the absolute differences between actual and predicted values, assessing prediction accuracy.

RMSE (Root Mean Squared Error): Measures the square root of the average squared differences between actual and predicted values, evaluating the magnitude of prediction errors.

# Technologies Used
pytrends: Used to fetch trend data for specific keywords using the Google Trends API.

matplotlib: Used to visualize the trend data and display temporal changes in graphs.

ARIMA: Used for forecasting time series data trends.

scikit-learn: Used to calculate MAE and RMSE to evaluate model prediction accuracy.

# Summary
Collected trend data for coffee-related keywords (such as espresso, latte, cappuccino) from Japan and Spain.

Visualized the data to understand the differences in trends across the two countries.

Applied the ARIMA model to forecast future trends and evaluated its accuracy using MAE and RMSE.

