# 📈 Stock Market Forecasting App  
**Time Series Forecasting with Prophet & Streamlit**

🔗 **Live Demo (Ngrok / Streamlit):** _temporarily available during runtime_  
📓 **Notebook (Colab):** Available in this repository  

---

## 📌 Project Overview

This project is an interactive **stock market forecasting web application** developed during an internship period.  
The application allows users to explore historical stock price data and generate short-term forecasts using Facebook Prophet.

The main goal of this project was to demonstrate how **time series forecasting models** can be integrated into a simple web application for exploratory financial analysis.

---

## 🧠 Business Context

Stock investors and analysts often need:
- Fast access to historical price movements
- Simple forecasting tools for short-term trend exploration
- Visual insights to support decision-making

This application addresses those needs by combining data retrieval, forecasting, and visualization into a single Streamlit app.

---

## 🛠️ Tech Stack

| Category | Tools |
|--------|------|
| Programming Language | Python |
| Web App Framework | Streamlit |
| Time Series Model | Prophet |
| Financial Data API | yFinance |
| Visualization | Plotly, Matplotlib, Cufflinks |
| Deployment (Temporary) | Ngrok (via Google Colab) |

---

## ⚙️ How the Application Works

1. **User selects a stock ticker** from a predefined list  
2. **Historical price data** is retrieved using `yfinance`
3. **Exploratory analysis**:
   - Raw price table
   - Bollinger Bands
   - Time series visualization
4. **Forecasting**:
   - Prophet model trained on historical closing prices
   - User selects forecast horizon (1–60 days)
5. **Model Evaluation**:
   - Cross-validation
   - Error metrics (MAPE, RMSE, MAE, SMAPE)

---

## 📊 Key Features

- Interactive stock selection
- Bollinger Bands visualization
- Adjustable forecasting horizon
- Prophet-based trend forecasting
- Model performance evaluation using cross-validation
- Web-based UI using Streamlit

---

## 📂 Project Structure

```text
Stockmarket-Forecasting-App-Prophet-Streamlit/
│
├── app.py                    # Main Streamlit application
├── *.ipynb                   # Google Colab notebook (development & testing)
├── README.md                 # Project documentation
└── assets/ (optional)        # Screenshots or visuals
```

---

## 🚀 How to Run Locally

Install all required dependencies:

pip install streamlit yfinance prophet plotly cufflinks
streamlit run app.py
Note: During development, this project was deployed temporarily using Ngrok on Google Colab.

---

## 🔍 Insights & Limitations
✅ Strengths
-End-to-end data workflow (data ingestion → modeling → web app)
-Clean integration between Prophet and Streamlit
-Suitable for exploratory time series forecasting
---
⚠️ Limitations
-Forecasts are not intended for financial or investment advice
-Prophet assumes trend continuity and may underperform in highly volatile markets
-Deployment setup is not production-grade (demo / experimental only)
---
📌 Author
Maulana Firman Nurdiansyah
Data Analyst | Data Enthusiast

📫 LinkedIn: [()](https://www.linkedin.com/in/m-firman-n/)
📁 GitHub: (this repository)

This project is part of a personal portfolio and reflects skills developed during an internship period.
