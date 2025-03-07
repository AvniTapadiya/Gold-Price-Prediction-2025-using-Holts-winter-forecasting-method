**Gold Price Prediction (2025) using Holt-Winters Method**

**Project Overview:-**

This project forecasts gold prices for the year 2025 using historical data from 2014 to 2024. The Holt-Winters method of forecasting is applied to analyze trends and seasonality in gold prices. The dataset is cleaned and processed using Python before performing time-series forecasting, and insights are visualized using a Power BI dashboard.

**Key Features:-**
- Data Preprocessing:
  - Merged two datasets: gold prices.csv and Gold Futures Historical Data (23.01.24-22.11.24).csv.
  - Cleaned and stored the processed data in merged_gold_prices.xlsx.
- Time-Series Data Preparation:
  - Monthly average prices calculated and stored in holtswinter.xlsx.
  - Time-series data structured as Month-Year format (e.g., 01/01/2014, 01/02/2024, etc.).
- Forecasting using Holt-Winters Method:
  - Applied Holt-Winters exponential smoothing model for gold price predictions.
  - Analyzed trend and seasonality in historical price data.
- Power BI Dashboard:
  - Visualized historical trends and predicted prices.
  - Gold Futures Historical Data (23.01.24-22.11.24).csv (futures market data).

**Technical Highlights:-**
- Data Sources:
  - gold prices.csv (historical gold prices from 2014-2024).
  - Gold Futures Historical Data (23.01.24-22.11.24).csv (futures market data).
- Technologies Used:
  - Python (Goldpricedatacleaning.ipynb) for data cleaning and merging.
  - Holt-Winters method for forecasting.
  - Power BI for visualization.
  - Excel/CSV files for storing structured data.

**Visualization:-**

Example: Power BI Dashboard.
The interactive dashboard provides insights into historical gold price trends and future predictions based on Holt-Winters analysis.

**How to Use:-**
- Download the .pbix file from the repository.
- Open it in Power BI Desktop.
- Load the dataset (holtswinter.xlsx).
- Explore historical trends and forecasted gold prices.

**Findings:-**
- The historical data from 2014 to 2024 shows a steady increase in gold prices, with significant growth after 2020.
- The Holt-Winters model captures both trend and seasonal fluctuations effectively.
- The forecast for 2025 suggests an initial rise in gold prices, followed by a potential decline towards the end of the year.
- Maximum predicted gold price for 2025 is around 2.7K, while the minimum is around 1.07K.
- Errors in the prediction remain low until 2024 but show a noticeable dip in 2025, indicating potential external market influences.

**Future Work:-**
- Incorporate external factors such as inflation, interest rates, and global economic trends to refine predictions.
- Compare Holt-Winters predictions with other forecasting models like ARIMA, Prophet, and LSTM.
- Develop an automated pipeline for real-time gold price forecasting and trend analysis.

**Acknowledgments:-**

Data Sources: gold prices.csv, Gold Futures Historical Data (23.01.24-22.11.24).csv from Kaggle.

