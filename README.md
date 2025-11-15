# Forecasting Electricity Prices Using LSTM (Time Series Analysis)

This project focuses on predicting future electricity prices using **Long Short-Term Memory (LSTM)**, a deep learning model designed for working with sequential and time-dependent data.

---

## 🔍 Problem Statement
Electricity price prediction is a **time series forecasting** problem. Prices change over time based on demand, weather, consumption patterns, and many other factors.  
The main goal is to **capture these temporal patterns** and predict future prices accurately.

---

## 🧠 Why LSTM?
LSTM is a special type of Recurrent Neural Network (RNN) that can remember long-term patterns.  
It is an ideal choice for this project because:

- It handles long-term dependencies  
- It works well with sequential data  
- It can learn trends and seasonality in time series  

---

## 🛠️ Project Workflow
### **1. Data Cleaning**
- Remove irrelevant or highly correlated features  
- Handle missing values  
- Normalize and prepare data for training  

### **2. Feature Engineering**
- Convert time series into supervised format  
- Create input windows for LSTM model  

### **3. Model Training**
- Build an LSTM model in Keras/TensorFlow  
- Train on historical electricity price data  
- Tune model with parameters like epochs, batch size, layers  

### **4. Forecasting**
- Use the trained model to predict future electricity prices  
- Visualize trends and forecast results  

---

## 📈 Results
The model learns patterns from historical data and predicts future prices with good accuracy.  
Visualizations are included to compare real vs predicted values.

---

## 📦 Technologies Used
- Python  
- NumPy, Pandas  
- Matplotlib  
- TensorFlow / Keras  
- Scikit-learn  

---

## 📂 Files in This Project
- `notebook.ipynb` — Main LSTM model, training & forecasting steps  
- `data/` — Dataset used for training  
- `README.md` — Project documentation  

---

## 💡 Conclusion
LSTM-based models are powerful for time-series forecasting.  
This project shows how deep learning can help understand and predict electricity pricing patterns effectively.

---

## ✨ Author
**Priyanka Kataria**

