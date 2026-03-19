# Time-series-Forecasting
# 📊 Walmart Sales Forecasting

## 🎯 Project Overview

This project focuses on predicting future Walmart sales using time series forecasting techniques.
It involves data preprocessing, visualization, and building predictive models to analyze trends and forecast future demand.

---

## 📂 Dataset

The dataset includes:

* Store and department-wise sales data
* External factors such as temperature, fuel price, and holidays
* Store details like type and size

---

## 🧹 Data Processing

* Merged multiple datasets (train, features, stores)
* Converted date column to datetime format
* Handled missing values
* Aggregated sales to create time series data

---

## 📈 Data Visualization

* Visualized sales trends over time
* Identified seasonal patterns and fluctuations
* Used line plots to understand sales behavior

---

## 🤖 Models Used

### 🔹 ARIMA (AutoRegressive Integrated Moving Average)

* Used as a baseline forecasting model
* Captures trends in time series data

### 🔹 Prophet (by Meta)

* Advanced forecasting model
* Automatically captures trend and seasonality
* Handles real-world data effectively

---

## 📊 Model Evaluation

* Evaluated using RMSE (Root Mean Squared Error)
* RMSE helps measure prediction accuracy
* Lower RMSE indicates better performance

---

## 📌 Key Insights

* Sales show strong seasonal patterns
* Weekly trends are clearly visible
* ARIMA provides baseline forecasting
* Prophet captures seasonality more effectively
* Forecast suggests stable future demand

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib
* Statsmodels (ARIMA)
* Prophet
* Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries

   ```bash
   pip install pandas numpy matplotlib statsmodels prophet
   ```
3. Open the notebook
4. Run all cells

---

## 🎯 Conclusion

This project demonstrates how time series forecasting can be applied to predict future sales and support data-driven business decisions.

---

## 👩‍💻 Author

**Nandini Gajendra**
