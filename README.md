# Stock-Price-Analysis
Welcome to the **Stock Price Analysis** project! This repository contains a Python-based analysis of historical stock price data. The project includes data cleaning, statistical analysis, and various visualizations to help understand trends, relationships, and performance metrics of AAPL stock.

In this project, you will find code to perform the following tasks:

- Load and preprocess historical stock price data.
- Generate descriptive statistics for the dataset.
- Create visualizations for stock price trends, trading volumes, and correlations.
- Compute and visualize moving averages and daily returns.
- Analyze and report on the average daily return and volatility of the stock.

## Requirements

To run this project, you will need Python and the following packages:

- `pandas` - For data manipulation and analysis.
- `matplotlib` - For creating static, animated, and interactive visualizations.
- `seaborn` - For statistical data visualization.
  
## Analysis Performed

The `main.py` script performs the following analyses:

1. **Load Data**:
   - Reads the CSV file containing historical stock price data.

2. **Data Cleaning and Preparation**:
   - Converts the `date` column to a `datetime` object and sets it as the index of the DataFrame.

3. **Summary Statistics**:
   - Displays descriptive statistics for key stock price metrics, including `open`, `high`, `low`, `close`, `adj_close`, and `volume`.

4. **Visualizations**:
   - **Stock Closing Price Over Time**: Line plot showing the closing price of stock over time.
   - **Stock Trading Volume Over Time**: Bar plot showing the trading volume of stock over time.
   - **Correlation Heatmap**: Heatmap showing correlations between different stock price metrics.
   - **Stock Price and Moving Averages**: Line plot with closing price and 20-day & 50-day Simple Moving Averages (SMAs).
   - **Daily Returns**: Line plot of the daily percentage change in closing price.

5. **Performance Metrics**:
   - Calculates and prints the average daily return and volatility of stock.

## Example Output

Running the `main.py` script will produce plots such as:

- A line plot of the closing price over time.
- A bar plot of the trading volume.
- A heatmap showing the correlation between different stock price metrics.
- A line plot showing the closing price along with 20-day and 50-day moving averages.
- A plot of daily returns.

Additionally, the script will print the following metrics:

```plaintext
Average Daily Return: 0.00052
Volatility: 0.01712
```


