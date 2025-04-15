
# ⚡ AI-Based Electricity Demand Forecasting for Delhi

This project focuses on forecasting electricity demand in **Delhi**, a city known for its extreme climatic conditions, rapid urbanization, and high energy consumption. The objective is to use **AI-based predictive models** to optimize energy distribution, prevent blackouts, and promote sustainable energy usage.

---

## 📌 Project Overview

**Objective:**  
With the increasing demand for electricity and the unpredictability of various factors such as weather, population growth, and consumer behavior, this project seeks to develop AI-based models that predict electricity demand, enabling better planning, efficiency, and grid stability in Delhi.

**Problem Statement:**  
Traditional forecasting tools fail to capture complex, non-linear relationships among multiple influencing factors. This leads to inefficiencies in energy consumption and increases the risk of grid failures during peak demand. AI models, particularly **LSTM**, can offer more accurate predictions and help in balancing energy distribution.

**Impact:**  
- Prevent blackouts during high-demand periods  
- Decrease the cost of overproduction or underutilization of energy  
- Support the integration of renewable energy sources into the grid  
- Promote environmentally friendly energy practices

---

## 📊 Tools & Technologies

- **Languages:** Python  
- **Libraries/Frameworks:** TensorFlow, Keras, Pandas, NumPy, Scikit-learn  
- **Models Used:**  
  - **LSTM (Long Short-Term Memory)**  
  - **Random Forest**  
  - **ARIMA (AutoRegressive Integrated Moving Average)**  

---

## 🔬 Methodology

1. **Data Collection & Preprocessing:**  
   - Collected data from multiple sources (weather, population growth, consumer behavior)  
   - Cleaned and normalized the data for training

2. **Model Training:**  
   - **LSTM:** Best for capturing sequential dependencies in time-series data  
   - **Random Forest:** Robust against non-linear patterns, though less suited for temporal dependencies  
   - **ARIMA:** A traditional linear model, but limited in capturing dynamic, non-linear patterns

3. **Model Evaluation:**  
   - **LSTM:** MAE = 145 MW, RMSE = 210 MW  
   - **Random Forest:** MAE = 160 MW, RMSE = 235 MW  
   - **ARIMA:** MAE = 175 MW, RMSE = 250 MW

---

## 📈 Results & Discussion

- **LSTM Performance:**  
  The LSTM model demonstrated the best performance, accurately capturing temporal dependencies in electricity demand over time, with minimal deviation from actual demand during both peak and off-peak periods.

- **Random Forest:**  
  Random Forest performed well with a slightly higher error compared to LSTM. It was able to handle non-linear relationships but lacked the temporal awareness that LSTM provided.

- **ARIMA:**  
  ARIMA's linear assumptions couldn't model the dynamic, non-linear nature of electricity demand, leading to a less accurate forecast.

### **Key Insights:**  
- **LSTM's Superiority:** The ability to learn from past sequences and predict future demand with high accuracy.  
- **Random Forest's Stability:** A strong alternative when LSTM isn't an option, but it lacks the depth of time-series modeling.  
- **ARIMA's Limitations:** Better suited for simpler, linear datasets but struggles with complex, real-world data like electricity demand.



![image](https://github.com/user-attachments/assets/d3a1efaa-ba7c-422b-a7cb-6148fb0885f0)
