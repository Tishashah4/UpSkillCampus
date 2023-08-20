# Smart_CIty_Traffic_Forecasting

The provided code aims to predict future traffic patterns based on historical data. It begins by reading the training dataset and performing feature engineering, extracting relevant information such as date, time, day of the week, month, and year from the DateTime column. The code then explores the data through various visualizations and statistical analyses to gain insights into the traffic patterns.

Next, the code splits the data into training and testing sets and trains four different machine learning models: Linear Regression, Decision Tree Regression, Random Forest Regression, and Neural Network Regression. The performance of each model is evaluated using mean absolute error (MAE) and root mean squared error (RMSE) metrics.

The code also reads a separate dataset containing future dates and applies the trained models to forecast the traffic patterns for these future dates. It visualizes the predicted traffic patterns for each junction and provides average traffic by day of the week, by month, and by junction.
