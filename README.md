# 📈 Stock Price Prediction using LSTM, ANN & Facebook Prophet

This project implements advanced time-series forecasting models to predict **Amazon stock prices**, leveraging deep learning and statistical methods. The objective is to compare model performance and analyze trend prediction accuracy.

---

## 🚀 Overview

* **Models Used:**

  * **LSTM (Long Short-Term Memory):** Deep learning model for sequence data and capturing temporal dependencies.
  * **ANN (Artificial Neural Network):** Baseline neural model for non-linear relationships in financial data.
  * **Facebook Prophet:** Additive regression model suitable for trend, seasonality, and holiday effects.

* **Techniques:**

  * Time-series decomposition
  * Feature engineering (lag features, rolling statistics)
  * Trend and seasonality analysis
  * Hyperparameter tuning

---

## 💡 Key Features

* Predicts future Amazon stock closing prices using different forecasting approaches.
* Visualizes model performance through plots of predicted vs actual values.
* Compares strengths and weaknesses of each model, highlighting LSTM’s sequence learning and Prophet’s trend detection.

---

## 🗂️ Dataset

* **Source:** Yahoo Finance (Amazon historical data)
* **Features:** Date, Open, High, Low, Close, Volume

---

## ⚙️ Project Structure

```
├── Stock_Prediction.ipynb      # Main notebook with all models and analysis
├── data/                       # (Optional) Downloaded or preprocessed data files
├── models/                     # (Optional) Saved model weights
├── results/                    # Plots and comparison metrics
└── README.md                   # This file
```

---

## 📈 Results

| Model   | MAE (Example) | Comments                               |
| ------- | ------------- | -------------------------------------- |
| LSTM    | \~22          | Best for capturing sequential patterns |
| ANN     | \~35          | Weaker on temporal dynamics            |
| Prophet | \~28          | Strong on long-term trend components   |

*Metrics may vary depending on final hyperparameters and training window.*

---

## ✅ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/stock-price-prediction.git
   cd stock-price-prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Download Amazon stock data (or load from `data/` folder).
4. Open and run `Stock_Prediction.ipynb` in Jupyter or Google Colab.

---

## 🔬 Future Work

* Integrate sentiment analysis from news or social media data.
* Include more technical indicators (e.g., RSI, MACD) as features.
* Explore hybrid ensemble approaches combining statistical and deep learning predictions.

---

## 📄 License

This project is for educational and research purposes only. Not intended for financial advice or real trading decisions.

---

## 🙏 Acknowledgments

* [Yahoo Finance](https://finance.yahoo.com/) for stock data
* Facebook Prophet and Keras/TensorFlow communities for open-source libraries
