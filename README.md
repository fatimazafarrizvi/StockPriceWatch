# 📈 PriceWatch – Stock Price Anomaly Detection

**PriceWatch** is a time-series anomaly detection project that analyzes stock price behavior to identify irregularities. Using historical stock data, this model helps flag sudden spikes, crashes, or unusual market activity—empowering investors and analysts to act proactively.

> Built using Python, Pandas, and Matplotlib to visualize and detect anomalies in historical stock price data.

---

## 🔍 Project Objective

The objective is to detect anomalies in the price patterns of stock data using statistical techniques such as:

- Rolling average deviation
- Z-score thresholding
- IQR-based outlier detection

This helps in:
- Detecting unusual price movements
- Gaining insights into potential market manipulation or events
- Improving risk management

---

## 🛠️ Technologies Used

- **Python** 🐍
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical analysis
- **Matplotlib / Seaborn** – Data visualization
- **SciPy (optional)** – Statistical analysis
- **Jupyter Notebook** – Interactive coding environment

---

## 📂 Dataset

We use real historical data of HDFC Bank’s stock prices.

🔗 **Dataset**: [HDFCBANK.NS.csv](https://github.com/fatimazafarrizvi/StockPriceWatch/blob/main/HDFCBANK.NS.csv)

It includes:
- `Date`
- `Open`, `High`, `Low`, `Close` prices
- `Adj Close`
- `Volume`

---

## 🧪 Methodology

1. Load and preprocess the dataset
2. Calculate moving averages and standard deviations
3. Apply anomaly detection using:
   - **Z-score**
   - **IQR (Interquartile Range)**
   - **Rolling Mean & Deviation**
4. Visualize the anomalies
