# 🥛 Milk Production Forecasting using RNN, LSTM & GRU

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-RNN%20LSTM%20GRU-green)
![Time Series](https://img.shields.io/badge/Time%20Series-Forecasting-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project focuses on forecasting **monthly milk production** using deep learning models:

- Simple RNN
- LSTM (Long Short-Term Memory)
- GRU (Gated Recurrent Unit)

The goal is to compare model performance and generate accurate future predictions.

---

## 🎯 Business Problem

A dairy business needs to predict future milk production to:

- Optimize supply chain and distribution
- Manage inventory efficiently
- Plan workforce and operations
- Handle seasonal demand variations

---

## 🎯 Objective

To build a **time series forecasting system** that predicts future milk production and supports data-driven decision-making.

---

## 📂 Dataset Description

The dataset contains:

- Monthly timestamps
- Milk production values

---

## 🔍 Exploratory Data Analysis (EDA)

- Time series trend visualization
- Seasonality pattern identification
- Missing values and duplicates check

---

## 🧹 Data Preprocessing

- Converted date column to datetime format
- Set time index
- Normalized data using MinMaxScaler
- Created time sequences (windowing)

---

## 🧠 Deep Learning Models

### 🔹 RNN (Recurrent Neural Network)
- Captures short-term dependencies
- Simple architecture

### 🔹 LSTM
- Handles long-term dependencies
- Solves vanishing gradient problem

### 🔹 GRU
- Faster and efficient alternative to LSTM
- Comparable performance

---

## ⚙️ Model Training

- Train-test split (80-20)
- Sequence window: 12 months
- Optimizer: Adam
- Loss function: Mean Squared Error (MSE)

---

## 📈 Model Evaluation

Metrics used:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

Models are compared based on prediction accuracy.

---

## 📊 Visualization

- Actual vs Predicted values
- Model comparison plots
- Forecast visualization

---

## 🔮 Future Forecasting

- Predicted milk production for next 12 months
- Visualized future trend

---

## 💡 Business Insights

- Helps in demand planning
- Reduces wastage
- Improves operational efficiency
- Supports strategic decision-making

---

## 🛠️ Tech Stack

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## ▶️ How to Run

git clone https://github.com/your-username/milk-production-forecasting-rnn-lstm-gru.git

pip install -r requirements.txt

Run jupyter notebook

---

## 📌 Future Improvements

Hyperparameter tuning
Add confidence intervals
Deploy using Streamlit
Use advanced models (Prophet, Transformer)

---

## 👩‍💻 Author

Meghana C Varghese
Data Scientist | Machine Learning Enthusiast

