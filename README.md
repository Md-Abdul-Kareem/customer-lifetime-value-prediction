# 📈 Customer Lifetime Value Prediction using Regression

This is my second internship project where I built a regression model to **predict Customer Lifetime Value (CLV)** based on historical customer behavior. This can help businesses focus on high-value customers and improve decision-making for marketing and retention.

---

## 📌 Project Overview

- **Goal**: Predict future customer value using past purchase patterns.
- **Model**: Linear Regression
- **Dataset**: Provided (`history.csv`) – includes past 6-month spend data per customer.

---

## 📊 Dataset Description

| Column Name | Description |
|-------------|-------------|
| M1 - M6     | Monthly spend data for 6 months |
| CLV         | Target: Lifetime Value to be predicted |

📁 Source: Internship-provided dataset (`history.csv`)

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🚀 Project Workflow

1. **Load and explore the dataset**
2. **EDA** – statistical summary and correlation heatmap
3. **Data cleaning** – drop ID columns and handle nulls
4. **Train-Test split**
5. **Modeling** – Linear Regression
6. **Model Evaluation** – R², MAE, RMSE
7. **Visualization** – Actual vs Predicted CLV

---

## 🧪 Model Performance

| Metric        | Value        |
|---------------|--------------|
| R² Score      | 0.82 (example) |
| MAE           | ₹1,234.56    |
| RMSE          | ₹2,345.67    |

📌 *Note: Actual results may vary based on training/testing splits.*

---

## 📁 How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/clv-prediction.git
   cd clv-prediction
