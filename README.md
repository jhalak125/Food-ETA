# 🍔 FoodETA – Food Delivery Time Prediction App

FoodETA is a Machine Learning–based web application that predicts the **estimated food delivery time (ETA)** based on order details, delivery person information, location, city conditions, traffic density, and weather conditions.  
The application is built using **Python, XGBoost, and Streamlit**. 👉 [Live Streamlit App]([https://your-app-link.streamlit.app](https://food-eta-ht74mnog6imxqfd9wby3nf.streamlit.app/))



---

## 📌 Project Overview

Accurate food delivery time prediction is crucial for improving customer satisfaction and optimizing delivery operations.  
FoodETA leverages data preprocessing, feature engineering, and a regression-based ML model to estimate delivery time efficiently.

### 🔍 Key Highlights
- End-to-end ML pipeline (data cleaning → feature engineering → modeling)
- Handles real-world issues like missing values and midnight time crossings
- Interactive web interface using Streamlit
- Trained using **XGBoost Regressor**

---

## 🧠 Machine Learning Model

- **Algorithm:** XGBoost Regressor  
- **Problem Type:** Regression  
- **Target Variable:** `Time_taken(min)`

### 🛠 Features Used
- Order date & time
- Pickup time
- Delivery person age & ratings
- Weather conditions
- Road traffic density
- City type
- Distance between restaurant and delivery location
- Multiple deliveries
- Festival indicator
- Vehicle type & condition


