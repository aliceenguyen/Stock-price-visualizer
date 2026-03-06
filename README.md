# Stock-price-visualizer
A Python-based financial data visualization tool that fetches historical stock prices for selected Hong Kong blue-chip companies and generates visual charts of their recent performance.

The program retrieves market data using the **yFinance API**, processes the dataset with **Pandas**, and produces multi-panel visualizations using **Matplotlib** to display stock trends over the last 10 trading days.

---
## 🚀 Features

- Fetches historical stock price data from Yahoo Finance
- Processes and cleans financial data using **Pandas**
- Automatically exports structured datasets to **CSV**
- Generates multi-panel **Matplotlib charts** for visualizing stock price trends
- Displays the most recent **10 trading days** of market activity
- Includes logging and error handling to ensure reliable execution

---
## 🛠 Tech Stack

- **Python**
- **Pandas**
- **Matplotlib**
- **yFinance**

---
## 📊 Example Output

The program generates two outputs:

**1. CSV Dataset**
Contains structured historical price data for the selected stocks.

**2. Chart Visualization**

A multi-panel chart displaying price movements for each stock across the last 10 trading days.

Example stocks visualized:

- CKH Holdings (0001.HK)
- CLP Holdings (0002.HK)
- HK & China Gas (0003.HK)
- HSBC Holdings (0005.HK)

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/stock-price-visualizer.git
cd stock-price-visualizer
Install dependencies:
pip install pandas matplotlib yfinance
▶️ Run the Program
pythonstock_price_visualizer.py
## 📂 Project Structure
stock-price-visualizer
│
├── stock-price-visualizer.py
├── stock_prices.cs
├── stock_prices.png
└── README.md
##💡Future Improvements
- Add interactive charts using Plotly
- Support additional stock markets and tickers
- Build a web dashboard for real-time visualization
- Implement automated daily data updates
