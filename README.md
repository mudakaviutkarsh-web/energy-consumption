# energy-consumption
# energy-consumption-prediction
# ⚡ Energy Consumption Time-Series Forecasting Application

## 🎯 Project Objective
The primary objective of this Streamlit application is to provide an interactive, end-to-end Machine Learning pipeline for analysis and forecasting of hourly electricity consumption (PJME region). 

Using historical data, the application automatically extracts time-series features (such as hour, day of the week, month, and season), performs exploratory data analysis, and trains an **XGBoost Regressor** to forecast future energy demands and evaluate feature importance in real-time.
<img width="1364" height="638" alt="image" src="https://github.com/user-attachments/assets/c855e560-7d6b-4f24-85de-02ad17f053e8" />
<img width="1366" height="641" alt="image" src="https://github.com/user-attachments/assets/ab522876-502c-441c-a39a-b11400e56166" />
<img width="1366" height="646" alt="image" src="https://github.com/user-attachments/assets/17cb135e-1677-4c16-9738-11d1735a51cd" />
<img width="1364" height="639" alt="image" src="https://github.com/user-attachments/assets/dba5b456-9348-4e80-a19d-05b3ae7f0aac" />

---

## ✨ Key Features
* **Interactive Data Exploration:** Upload custom hourly time-series CSV datasets or utilize default historical energy usage data.
* **Exploratory Visualizations:** Analyze hourly and seasonal energy consumption trends using interactive plots and boxplots.
* **Dynamic Model Training:** Adjust train/test split years, hyperparameter configurations (estimators, learning rate), and train an XGBoost model directly from the UI.
* **Feature Importance Analysis:** Measure which temporal attributes (e.g., hour of day vs. month of year) drive peak energy demand.

---

## 🛠️ Requirements & Installation

Ensure you have Python 3.8+ installed. Install the required dependencies using pip:

```bash
pip install streamlit pandas numpy matplotlib seaborn xgboost scikit-learn
