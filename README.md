# ✈️ Delta Airlines Future Traffic Forecasting (LSTM Model)

This project uses an LSTM (Long Short-Term Memory) neural network to forecast monthly traffic for **Delta Airlines** using historical data from 1990 to 2024.

We analyze seasonal trends, detect patterns, and predict traffic for the next 12 months(2025).

---

## 📊 Dataset

The data comes from the U.S. International Airline Traffic Statistics dataset and includes:
- Airline name
- Traffic type (passenger, freight, etc.)
- Scheduled vs charter flights
- Monthly totals (1990–2024)

---

## 🧠 Machine Learning Model

We used a Recurrent Neural Network (LSTM) to:
- Capture long-term trends and seasonality
- Forecast 12 months of traffic based on previous values

Steps:
1. Data cleaning and monthly aggregation
2. Scaling with `MinMaxScaler`
3. Sequence creation for time-series modeling
4. LSTM model built using TensorFlow
5. Forecast generation and plotting

---

## 📁 Files

- `LSTM Model.ipynb` — Full code
- `delta_airlines_forecast.csv` — Forecast output
- `README.md` — This file :)

---
## 🔮 Results

- The model tracks real traffic closely, even during pandemic dips.
- Forecasted traffic shows a steady upward trend.
- Visualization includes both historical and forecasted data.

---
## 📈 Evaluation Metrics

- RMSE: 456,716.49
- MAE: 313,446.80
- R² Score: 0.8857

---
## 🙋‍♂️ Author

Narasimha Royal 

---
