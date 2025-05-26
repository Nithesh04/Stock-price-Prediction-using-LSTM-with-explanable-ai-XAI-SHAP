# 📈 HDFC Bank Stock Price Prediction using LSTM with Explainable AI

This project uses an LSTM (Long Short-Term Memory) deep learning model to forecast HDFC Bank stock prices based on historical closing prices. It integrates **SHAP (SHapley Additive exPlanations)** to make model predictions interpretable, enabling insight into how past stock movements influence future forecasts.

---

## 🚀 Features

- LSTM-based time series forecasting model
- Predicts next **10-day** and **30-day** stock prices
- Visualizations for actual vs predicted prices
- SHAP explainability: Waterfall, Bar, and Custom Contribution Plots
- Evaluation metrics: MAE, MSE, RMSE, R² Score

### 10days Forecast: 
![Image](https://github.com/user-attachments/assets/14e8cdf9-3bf7-4093-9eaa-6809c973ecfe)

### 30days Forecast:
![Image](https://github.com/user-attachments/assets/bd06f0f1-a06e-4f67-b4f9-edb0d2ec368a)

---

## 🛠️ Technologies Used

- **Python**
- **TensorFlow / Keras** – LSTM model
- **NumPy**, **Pandas** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **SHAP** – Model explainability
- **scikit-learn** – Data scaling & evaluation metrics

---

## 📊 Model Architecture

- Input: 100 previous days of stock closing prices
- LSTM Layers: 2 stacked LSTM layers with Dense output
- Output: 1-day prediction fed autoregressively for multi-step forecasting

---

## 📈 Results & Visualizations

- Plots of actual vs predicted stock prices
- 10-day and 30-day forecast graphs
- SHAP Waterfall & Bar plots highlighting the most influential past time steps
- Custom bar chart showing positive vs negative contributions per day

---

## 💡 Explainable AI with SHAP

SHAP explains the contribution of each input (past stock value) to the model's final prediction.

- **Waterfall Plot**: Breaks down how each day impacts the prediction
![Screenshot 2025-05-24 124517](https://github.com/user-attachments/assets/0b9c8d3c-4633-4a2e-992d-433cb5a8eddf)

- **Bar Plot**: Ranks time steps by importance
![Screenshot 2025-05-24 124714](https://github.com/user-attachments/assets/5e39a967-53df-4e41-9e46-240d7c089cb3)
![Screenshot 2025-05-24 125924](https://github.com/user-attachments/assets/b28883db-d95c-45b7-b44e-27a304791d37)


---

## 🧪 Evaluation Metrics

| Metric     | Description                          |
|------------|--------------------------------------|
| MAE        | Mean Absolute Error                  |
| MSE        | Mean Squared Error                   |
| RMSE       | Root Mean Squared Error              |
| R² Score   | Coefficient of Determination         |

---

## 🔧 Usage

Follow the steps below to run the HDFC Bank stock price prediction model and interpret it using SHAP:

### 1. Clone the Repository

```bash
git clone https://github.com/Nithesh04/Stock-price-Prediction-using-LSTM-with-explanable-ai-XAI-SHAP.git
cd Stock-price-Prediction-using-LSTM-with-explanable-ai-XAI-SHAP
