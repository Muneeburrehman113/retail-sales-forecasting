# Retail Sales Forecasting

## 📌 Overview
This project focuses on building a **time series forecasting model** to predict monthly sales for a retail store. Using historical sales data from the last 4 years, the model forecasts the next 6 months, helping the store make better decisions in **inventory management** and **financial planning**.

## 📊 Objective
- Analyze historical sales patterns and seasonality.
- Compare different time series models for forecasting.
- Select the best-performing model based on accuracy metrics.
- Provide actionable forecasts to assist business decisions.

## 🛠 Methodology
1. **Data Preparation**
   - Cleaned and formatted 4 years of monthly sales data.
   - Checked for trends, seasonality, and anomalies.

2. **Modeling**
   - Tried multiple forecasting techniques:
     - **ETS (Exponential Smoothing)**
     - **SARIMA (Seasonal ARIMA)**
     - **Facebook Prophet**
   - Compared models using **MAE, RMSE, and MAPE**.

3. **Best Model Selection**
   - **ETS Model** performed the best, providing the most accurate predictions.

4. **Forecasting**
   - Predicted sales for the next **6 months** to support inventory and financial strategies.

## 📈 Results
- **ETS Model** achieved the lowest error metrics among tested models.
- Forecast shows potential sales growth in the upcoming months.
- Provides valuable insights for **stock optimization** and **budget planning**.

## 📂 Files in Repository
- `Retail_Sales_Forecasting.ipynb` → Jupyter Notebook with full analysis and model training.
- `sales_forecast_results.csv` → 6-month forecasted sales values.
- `model.pkl` → Saved ETS model for reuse.
- `data/` → Historical sales dataset (if allowed to share).

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/retail-sales-forecasting.git
   cd retail-sales-forecasting
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Retail_Sales_Forecasting.ipynb
   ```

## 📌 Future Improvements
- Experiment with **LSTM deep learning models**.
- Incorporate external factors like promotions, holidays, and market trends.
- Build a **dashboard** for interactive forecast visualization.
