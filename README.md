# 🏠 Household Energy Consumption Prediction

This project focuses on predicting **household electricity usage (kWh)** using real-world power consumption data.  
The goal is to clean, analyze, and prepare the dataset, then build and evaluate machine learning models for energy forecasting.

---

## 📊 Project Overview
- **Dataset:** UCI Individual Household Electric Power Consumption Dataset (2006–2010)  
- **Objective:** Predict household energy consumption using time-series power data  
- **Tools:** Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook  

---

## 🧹 Week 1 – Data Gathering and Cleaning
1. Downloaded and explored the dataset  
2. Replaced invalid entries and handled missing values  
3. Converted columns to correct numeric data types  
4. Combined Date and Time columns into a single `Datetime` index  
5. Interpolated and dropped null values  
6. Verified data continuity with time-series visualization  

**Output:** Cleaned dataset saved as `cleaned_household_power_consumption.csv`

---

## 🤖 Week 2 – Model Training and Evaluation
1. Split data into training (80%) and testing (20%) sets  
2. Trained **Linear Regression** and **Random Forest Regressor** models  
3. Predicted power consumption and compared results with actual data  
4. Evaluated accuracy using **MAE**, **RMSE**, and **R²** metrics  
5. Visualized actual vs predicted energy consumption  

**Results:**  
- Linear Regression → R² = 0.9980  
- Random Forest → R² = 0.9984 (higher accuracy and better fit)  

---

## 📈 Next Steps
- Perform detailed Exploratory Data Analysis (EDA)  
- Add feature engineering (hour, weekday, rolling averages)  
- Test advanced models like **XGBoost** or **LSTM**  
- Build a small dashboard (Streamlit/Flask) for visualization  

---

## 📚 Dataset Source
[UCI Machine Learning Repository – Individual Household Electric Power Consumption](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)

---

### 👩‍💻 Author
**Jhanvi**  
Internship Project — Week 1 & 2  
(Data Cleaning | Model Training | Evaluation)
