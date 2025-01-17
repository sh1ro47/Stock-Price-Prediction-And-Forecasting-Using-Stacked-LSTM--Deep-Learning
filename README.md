# Stock Market Prediction and Forecasting using Stacked LSTM

This repository contains a project that leverages **Stacked Long Short-Term Memory (LSTM)** models to predict and forecast stock prices. The project is implemented in Python and uses libraries like TensorFlow, Pandas, and Matplotlib.

---

## Features

- **Data Collection**: Fetch stock data using the Tiingo API.
- **Data Preprocessing**: Normalize the data using Min-Max Scaling.
- **Model Building**: Create a Stacked LSTM model with TensorFlow/Keras.
- **Training**: Train the model on historical stock data.
- **Evaluation**: Calculate performance metrics like RMSE.
- **Forecasting**: Predict future stock prices using the trained model.
- **Visualization**: Plot predictions and forecasts against actual stock prices.

---

## Installation

### Prerequisites
Ensure you have Python 3.7+ installed. Install the required dependencies:

```bash
pip install tensorflow pandas matplotlib numpy scikit-learn pandas_datareader
