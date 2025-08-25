#  Walmart Sales Forecasting

A time-series forecasting project to predict weekly store-level sales for Walmart using machine learning techniques. This project focuses on improving forecast accuracy to support inventory and promotional planning.

---

##  Objective

Use historical sales data to build and evaluate forecasting models that predict weekly sales at the store and department level.

---

##  Dataset Overview

- **Source:** Walmart sales data (e.g., including `store_id`, `dept_id`, `date`, `sales`)
- **Frequency:** Weekly sales data per store-department combination
- **Key Features:** Sales amount, store and department IDs, date/time indicators

---

##  Methodology

1. **Data Exploration & Preprocessing**
   - Loaded data and explored weekly sales patterns
   - Handled missing values and outliers where necessary
   - Engineered time-based features (e.g., month, year, seasonal indicators)

2. **Modeling Approaches**
   - **Baseline Models**: Simple methods like Naïve Forecasting or Moving Average
   - **Machine Learning Models**: Regression-based and ensemble algorithms
   - **Advanced Time-Series Models**: ARIMA, Prophet, or similar (if applied)

3. **Model Evaluation**
   - Used metrics like **MAPE**, **RMSE**, or **MAE** to assess accuracy
   - Visualized predicted vs. actual sales for validation

4. **Forecast Generation**
   - Generated future weekly sales forecasts for specified `store × dept` combinations
   - Visualized forecasts and trends

---

##  Results

- Performance summary of chosen models (e.g., **Model A achieved X% MAPE**, **Model B had lower RMSE**).
- Visual comparison of actual and predicted sales trends.

---

##  Tools & Libraries

- **Python, Jupyter Notebook**
- Pandas, NumPy for data processing
- Matplotlib / Seaborn for visualizations
- Scikit-learn for machine learning
- Statsmodels, Prophet, or similar time-series tools (if applicable)

---

##  How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Nisarga-s-m/Walmart_Sales_Forecasting-.git
   cd Walmart_Sales_Forecasting-
