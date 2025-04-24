# 📈 Sales Forecasting using Facebook Prophet

This repository contains an advanced time series forecasting model built with **Facebook Prophet**, aimed at predicting future sales for a retail business. It is developed as part of the **Future Interns Machine Learning Internship (Task 1)**.

---

## 🎯 Objective

The goal of this project is to:
- Forecast future sales trends based on historical data
- Understand seasonal and trend patterns in retail sales
- Evaluate model performance and improve forecast accuracy using advanced techniques

---

## 📂 Dataset Details

- **Filename**: `sales_data_sample.csv`
- **Source**: [Kaggle - Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
- **Type**: Real-world transactional data from a retail business

### 🧾 Key Columns Used:
| Column Name         | Description                              |
|---------------------|------------------------------------------|
| `ORDERDATE`         | Date of the order (used as `ds`)         |
| `SALES`             | Revenue generated (used as `y`)          |
| `QUANTITYORDERED`   | Number of units sold (used as regressor) |
| `PRICEEACH`         | Price per unit (used as regressor)       |

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Facebook Prophet** (forecasting)
- **Pandas & NumPy** (data manipulation)
- **Matplotlib** (visualization)
- **Scikit-learn** (evaluation metrics)

---

## 🚀 Features of the Model

- ✅ **Outlier Removal** using IQR filtering
- ✅ **Log Transformation** for variance stabilization
- ✅ **Holiday Effects** added (e.g., Christmas, Black Friday)
- ✅ **Custom Seasonality** (monthly & weekly)
- ✅ **External Regressors**: `QUANTITYORDERED`, `PRICEEACH`
- ✅ **Hyperparameter Tuning** (changepoint & seasonality priors)
- ✅ **Evaluation Metrics**: MAE, MAPE
- ✅ **Cross-validation** with Prophet’s diagnostics tools

---

## 📉 Forecasting Results

- Forecasted sales for the next **90 days**
- Visualized:
  - 📈 Predicted vs Actual Sales
  - 📊 Seasonality (weekly/monthly patterns)
  - 📊 Forecast components (trend, yearly, holidays)

---

## 📊 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/G1r1dhar/sales-forecasting.git
   cd sales-forecasting

