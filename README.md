# Currency Exchange Rate Prediction using Machine Learning

## 📌 Project Overview  
Currency exchange rates are highly volatile and influenced by various macroeconomic factors. This project leverages **machine learning techniques** to predict **currency exchange rates**, focusing on the **Indian Rupee (INR) exchange rate**. The goal is to provide accurate and reliable predictions that help businesses, investors, and policymakers make informed financial decisions.

## 📊 Dataset  
The dataset consists of **2632 rows** and **7 attributes**:  
- **Date** – The date of exchange rate observation.  
- **Price** – The INR exchange rate value on that date.  
- **Open** – The exchange rate at the start of the trading session.  
- **High** – The highest recorded exchange rate of the day.  
- **Low** – The lowest recorded exchange rate of the day.  
- **Volume (Vol.)** – The total number of trades made in the given period.  
- **Change (%)** – The percentage change in exchange rate compared to the previous day.  

## 🚀 Machine Learning Models Used  
The following machine learning models were implemented for exchange rate prediction:  
- **Seasonal Autoregressive Integrated Moving Average (SARIMA)**   

## 📈 Model Performance  
The accuracy of the models was evaluated using **Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, and **Mean Absolute Percentage Error (MAPE)**. The **SARIMA** model demonstrated strong performance in identifying seasonal trends, while **LSTM-based models** showed promise in capturing complex time-dependent patterns.  

## 🛠 Installation & Setup  
To run this project on your local system, follow these steps:

1. **Clone the Repository**  
   ```sh
   git clone https://github.com/PreranaSangar/currency-exchange-rate-prediction.git
   cd currency-exchange-rate-prediction
2.pip install -r requirements.txt
3.python main.py

📌 Features
Uses historical exchange rate data to make accurate forecasts.
Implements time series analysis and deep learning models.
Supports multi-currency exchange rate prediction.
Provides visualizations for better trend analysis.

📜 Conclusion
This project demonstrates that SARIMA and deep learning models (LSTM, RNN) can provide reliable exchange rate forecasts. These predictions can aid financial institutions, traders, and policymakers in making data-driven decisions, reducing risks associated with currency fluctuations.
