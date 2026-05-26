Financial Performance & Risk Analysis with PySpark
📌 Project Overview
This project provides a comprehensive financial evaluation of major technology stocks (AAPL, MSFT, GOOGL) using Big Data processing. The goal is to demonstrate the ability to handle financial time series, calculate risk metrics, and identify market trends (Alpha) using PySpark.

## 🛠️ Key Technical Features & Statistical Metrics
* **Data Ingestion:** Automated daily stock data extraction via Yahoo Finance API (`yfinance`).
* **Advanced Spark Window Functions:** Applied scalable partitioning and ordering to handle time-series data efficiently without moving data across clusters.
* **Risk & Performance Metrics Implemented:**
    * **Rolling Volatility:** Standard deviation of log daily returns to measure asset risk dynamic over time.
    * **Simple Moving Average (SMA 20):** Trend-following indicator to smooth out price action.
    * **Cumulative Returns (Base 100):** Performance tracking metric to isolate and analyze the "Alpha" (outperformance) of specific assets.

📈 Financial Insights (2024 - 2026)
Sector Correlation: During the first half of the period (until July 2025), the tech giants showed highly correlated movements, indicating a beta-driven market.

Google's Outperformance (GOOGL): From July 2025 onwards, Google demonstrated a significant "decoupling" from its peers, showing higher growth with controlled volatility.

Risk Assessment: The study identified specific volatility peaks, allowing for a better understanding of the risk-reward ratio for each asset.

🚀 How to Run
Open the notebook in Google Colab.

Install requirements: !pip install yfinance pyspark.

Run the cells to see the Spark DataFrame transformations and final visualizations.
├── notebooks/
│   └── Financial_Analysis_Spark.ipynb   # Main PySpark code
├── README.md                            # Documentation
└── requirements.txt                     # Project dependencies
---

## 👨‍💻 Autor
**Julimar Pedro de Oliveira**

* 🔵 [LinkedIn](https://www.linkedin.com/in/julimar-oliveira-59984a1a4/)
* 📧 [Email](julimarpoliveira@gmail.com)

---
