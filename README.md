# 📊 Lab Assignment 5 - Time Series Forecasting using LSTM

## 👨‍🎓 Name: Dhiraj Rathod  
## 🆔 PRN: 202201040139  
## 🧑‍🤝‍🧑 Group Members: Sanket Mane  
## 🧪 Batch: T3  

---

## ✅ Objective

Implement LSTM-based models for:

- Time series forecasting (Experiment 5.1)
- Sequence text generation (Experiment 5.2)
- Text classification (Experiment 5.3)

---

## 📁 Experiments Overview

### 🔹 **Experiment 5.1: Time Series Forecasting using LSTM**

**Dataset**: [Airline Passengers](https://raw.githubusercontent.com/jbrownlee/Datasets/master/airline-passengers.csv)

- Forecasts future values based on past airline passenger data.
- Preprocessing using MinMaxScaler.
- LSTM model with 2 layers + Dense output.
- Evaluation using RMSE and MAE.
- Output: Actual vs Predicted plot.

📈 **Expected Output**:
- Line graph of actual vs predicted passenger count
- RMSE & MAE values printed

---

### 🔹 **Experiment 5.2: Sequence Text Prediction using LSTM**

**Dataset**: Shakespeare Sample Text

- Character-level text generation using LSTM.
- One-hot encoding of sequences.
- Model trained to predict next character in a sequence.
- Evaluation via generated text and training curves.

📜 **Expected Output**:
- Auto-generated Shakespeare-like text
- Training Loss & Accuracy plot

---

### 🔹 **Experiment 5.3: Sequence Text Classification using LSTM**

**Dataset**: [SMS Spam Collection Dataset](https://raw.githubusercontent.com/justmarkham/DAT8/master/data/sms.tsv)

- LSTM-based binary classification model.
- Tokenization and padding of input sequences.
- Model evaluated using accuracy, precision, F1-score.
- Confusion matrix visualization using seaborn.

📊 **Expected Output**:
- Classification report (Precision, Recall, F1-score)
- Confusion matrix heatmap
- Loss/Accuracy curves for train and validation

---

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- TensorFlow / Keras
- Scikit-learn

---

## 📌 How to Run

1. Make sure all required libraries are installed:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
