Sure. Based on your **Shopify OHLC analysis notebook**, here is a clean, professional README you can copy-paste. I’ve used **Author: Archana Devi M** as requested.

# Shopify Stock OHLC Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Shopify stock market data using Python. The analysis focuses on **Open, High, Low, Close (OHLC)** prices, trading volume, moving averages, daily returns, and rolling volatility.

The project helps understand Shopify's stock price movements and identify basic trends and volatility patterns over time.


## 🎯 Objectives

* Analyze Shopify stock price data.
* Understand Open, High, Low, and Close (OHLC) prices.
* Visualize stock price movements over time.
* Analyze trading volume.
* Calculate 20-day and 50-day moving averages.
* Calculate daily stock returns.
* Analyze the distribution of daily returns.
* Calculate and visualize 20-day rolling volatility.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data loading, cleaning, transformation, and analysis
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook**

## 📂 Dataset

The project uses a Shopify stock dataset containing stock market information such as:

* Date
* Open Price
* High Price
* Low Price
* Close Price
* Trading Volume

The date column is converted into a datetime format and the dataset is sorted chronologically before analysis.

## 🔍 Data Analysis Performed

### 1. Data Inspection

The dataset is initially examined using:

* `head()` – View the first records
* `tail()` – View the last records
* `shape` – Check the number of rows and columns
* `describe()` – Generate statistical summaries
* `info()` – Check data types and dataset information

### 2. Date Processing

The `date` column is converted into a datetime format and the dataset is sorted according to the date.

### 3. OHLC Price Analysis

The **Open, High, Low, and Close** prices are plotted to visualize Shopify's stock price movement over time.

### 4. Trading Volume Analysis

Trading volume is visualized to understand how the number of traded shares changes over time.

### 5. Moving Average Analysis

Two moving averages are calculated:

* **MA20** – 20-day moving average
* **MA50** – 50-day moving average

These moving averages are plotted together with the closing price to observe price trends.

### 6. Daily Return Analysis

Daily returns are calculated using the percentage change in closing prices.

The formula used is:

```text
Daily Return = (Current Close - Previous Close) / Previous Close
```

The distribution of daily returns is visualized using a histogram with a KDE curve.

### 7. Rolling Volatility Analysis

A **20-day rolling volatility** is calculated using the standard deviation of daily returns.

This helps observe how the variability of Shopify's stock returns changes over time.

## 📊 Visualizations

The notebook includes visualizations for:

1. Shopify OHLC Stock Prices
2. Shopify Trading Volume
3. Shopify Closing Price
4. 20-Day and 50-Day Moving Averages
5. Distribution of Daily Returns
6. 20-Day Rolling Volatility

## 📁 Project Structure

```text
Shopify-OHLC-Analysis/
│
├── Shopify EDA 4.ipynb
├── shopify_stock.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone or download the repository.
2. Install the required Python libraries:

```bash
pip install pandas matplotlib seaborn jupyter
```

3. Place the `shopify_stock.csv` dataset in the project directory.
4. Open the notebook:

```bash
google colab notebook shopify_ohlc.ipynb
```

5. Run the notebook cells sequentially.

## 📈 Key Analysis Areas

The project demonstrates practical skills in:

* Data loading
* Data inspection
* Data cleaning and preprocessing
* Date and time handling
* Exploratory Data Analysis
* Financial data analysis
* Moving average calculation
* Return calculation
* Volatility analysis
* Data visualization

## 📝 Conclusion

This project provides a basic analysis of Shopify stock price data using Python. By examining OHLC prices, trading volume, moving averages, daily returns, and rolling volatility, the notebook demonstrates how financial time-series data can be explored and visualized to understand stock price behavior.

## 👩‍💻 Author

**Archana Devi M**
