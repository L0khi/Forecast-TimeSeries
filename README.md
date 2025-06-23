
# 📈 ForecastPro: Time Series Forecasting on Google Stock

ForecastPro is a complete time series forecasting solution built to predict future trends using statistical, machine learning, and deep learning models. It uses ARIMA, ETS, Prophet, Random Forest, XGBoost, and LSTM (PyTorch) to forecast stock prices and provides a visual dashboard using Streamlit.

## 🔧 Features

- 📊 Models: ARIMA, ETS, Prophet, LSTM, RandomForest, XGBoost
- 🧠 Meta-Ensemble for ultra-accurate forecasting
- 📉 Rolling stats, ACF/PACF, seasonal decomposition
- ✅ Evaluation: MAE, RMSE
- 🎯 Visualized results using Streamlit

## 🧠 Evaluation Metrics

| Model           | MAE    | RMSE   |
|----------------|--------|--------|
| ARIMA          | 23.21  | 28.14  |
| ETS            | 19.47  | 23.96  |
| Prophet        | 38.17  | 41.01  |
| Random Forest  | 6.50   | 11.76  |
| XGBoost        | 6.66   | 11.96  |
| LSTM (PyTorch) | 2.08   | 2.85   |
| Meta-Ensemble  | 1.55   | 2.06   |

## 🚀 Run the App

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 📁 Folder Structure

```
ForecastPro/
├── app.py
├── Google_data.csv
├── notebook/
│   └── Meta_model_best_google.ipynb
├── screenshots/
│   └── *.png
├── requirements.txt
└── README.md
```

## 👨‍💻 Author

Made by **[Lokhi](https://github.com/L0khi)** | ForecastPro v1.0
