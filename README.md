# 📈 Stock Price Predictor - Extended

This is a web-based application that provides stock data visualization, recent stock data, and future stock price predictions using various regression models. It leverages Streamlit for the user interface and yfinance for fetching stock market data.


## 📚 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Sections](#sections)
- [Project Structure](#project-structure)
- [Screenshot](#screenshot)
- [How to Use](#how-to-use)
- [Future Enhancements](#future-enhancements)

---

## 📝 About the Project

This **Stock Price Predictor** application allows users to:

Visualize stock prices with technical indicators such as Bollinger Bands, Moving Averages, MACD, and RSI.
Fetch and display the most recent stock data for a selected stock symbol.
Predict future stock prices using different machine learning models like Linear Regression, Random Forest, and XGBoost.

## ⭐ Features

- **📊 Technical Indicators**: Visualize key indicators such as MACD, Bollinger Bands, RSI, SMA, and EMA.
- **🔍 Recent Stock Data**: View the most recent data of a selected stock.
- **🔮 Stock Price Prediction**: Predict future stock prices using models like Linear Regression, Random Forest, and XGBoost.
- **🎛️ Customizable Input**: Select start and end dates, choose the duration, and the prediction model to forecast prices.

## 💻 Technologies Used

- **Frontend**: Streamlit
- **Backend**: Python
- **APIs**: yFinance
- **Libraries**: Scikit-learn, XGBoost, TA-Lib for indicators, Pandas, NumPy

## 📂 Sections

- **Visualize**: Display technical indicators of stocks.
- **Recent Data**: Show the last few rows of recent stock data.
- **Predict**: Predict future stock prices based on different models and forecast days.

## 🗂️ Project Structure


```bash
Copy code
├── images/                # Images used in the project
├── SMP.py                 # Main Python application
├── requirements.txt       # Python dependencies
└── README.md              # Project README
```

## 📸 Screenshot

![Stock Price Predictor Screenshot1](images/Screenshot1.png)

![Stock Price Predictor Screenshot2](images/Screenshot2.png)

![Stock Price Predictor Screenshot3](images/Screenshot3.png)

## 🛠️ How to Use

1. Clone the repository:

```bash
git clone https://github.com/pranay_1306/Stock-Market-Prediction.git
cd stock-price-predictor
```

2. Install dependencies:


```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
streamlit run SMP.py
```

## 🚀 Future Enhancements

- Add more models for prediction.
- Improve the accuracy of predictions.
- Add more stock market data visualizations.
- Enhance the UI with more interactive features.
