# 📈 Multi-Step Stock Price Forecasting using RNN and LSTM

## 📌 Overview
This project implements Deep Learning models for **multi-step stock price prediction** using historical time-series data.

Two neural network architectures are compared:

- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)

The objective is to evaluate and compare their ability to forecast future stock prices based on past closing prices.

---

## 🎯 Objective
- Perform multi-step stock price forecasting  
- Compare RNN and LSTM performance  
- Evaluate models using regression metrics  
- Analyze predictive capability on unseen test data  

---

## 📊 Dataset
- **Stock:** AZN.L (AstraZeneca)  
- **Data Source:** Yahoo Finance  
- **Time Period:** 2010 – 2020  
- **Training Period:** 2010 – 2016  
- **Testing Period:** 2017 – 2020  
- **Feature Used:** Closing Price  

### Forecasting Setup
- **Input Window:** 5 Days  
- **Output Horizon:** 2 Days  
- **Scaling Method:** MinMaxScaler  

---

## 🧠 Models Implemented

### 1️⃣ Recurrent Neural Network (RNN)
- 2 RNN layers  
- Dropout regularization  
- Dense output layer (2 neurons for multi-step prediction)  

### 2️⃣ Long Short-Term Memory (LSTM)
- 2 LSTM layers  
- Dropout regularization  
- Dense output layer (2 neurons)  

---

## 📏 Evaluation Metrics
The models were evaluated using:

- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  
- MAPE (Mean Absolute Percentage Error)  
- R² Score  
- Day-wise RMSE (Day 1 and Day 2)  

---

## 📈 Results
- LSTM achieved lower RMSE compared to RNN.  
- LSTM showed better generalization capability.  
- Results confirm literature findings that LSTM performs better for time-series forecasting.  

---

## 🛠 Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Yahoo Finance API  

---

## 🔮 Future Improvements
- Integrate Sentiment Analysis signals  
- Add technical indicators (RSI, MACD)  
- Experiment with GRU and Transformer models  
- Expand to multi-stock forecasting  

---

## 📎 Research Context
This implementation aligns with research exploring deep learning and sentiment-aware forecasting techniques for financial markets.
