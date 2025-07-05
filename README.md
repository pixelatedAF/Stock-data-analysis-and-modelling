# Stock-data-analysis-and-modelling
Project Title: TCS Stock Data Analysis and Prediction
Objective
Analyze the historical data of TCS stock to gain insights into stock behavior, identify trends, and forecast future stock prices.

Dataset Columns Explanation
1. Date - Date of trading data.
2. Open - Opening stock price on that day.
3. High - Highest stock price of the day.
4. Low - Lowest stock price of the day.
5. Close - Closing stock price of the day.
6. Volume - Number of shares traded.
7. Dividends - Dividends paid on the stock.
8. Stock Splits - Number of stock splits.

🔧 Steps Involved
1.Import Libraries
  Load essential Python libraries like pandas, matplotlib, and sklearn.

2.Load the Dataset
  Read historical stock data (CSV or API) into a DataFrame using pandas.
  > Explore & Clean the Data
  > Check for missing values
  > Convert date columns to datetime format
  > Sort data by date

3.Visualize Raw Stock Prices
  Plot the original closing prices using matplotlib to observe trends.

4.Normalize Prices
  Use StandardScaler to standardize stock price values for better comparison.

5.Plot Normalized Data
  Create time-series plots of normalized values to compare multiple stocks fairly.

6.Draw Insights
  Analyze trends, spikes, or patterns that may indicate market behavior.

7.Export or Save Data (Optional)
  Save processed or transformed datasets for future modeling or sharing.

Tools and Libraries used
~Numpy
~Pandas
~Matplotlib
~scikit-learn
