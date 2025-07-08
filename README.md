# 📈 Sales Prediction using Multiple Linear Regression

This project uses **Multiple Linear Regression** to predict product sales based on advertising budgets in **TV**, **Radio**, and **Newspaper** media.

---

## 📁 Dataset

- **Name:** Advertising Dataset (synthetic, 10,000 rows)
- **Features:**
  - `TV` – TV advertising budget
  - `Radio` – Radio advertising budget
  - `Newspaper` – Newspaper advertising budget
- **Target:**
  - `Sales` – Units sold (in thousands)

📥 File used: `advertising_10000.csv`

---

## ⚙️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🔍 Workflow

1. **Import libraries**
2. **Load and explore the dataset**
3. **Visualize correlations**
4. **Split data into training and testing sets**
5. **Scale features**
6. **Train a Multiple Linear Regression model**
7. **Predict and evaluate performance**
8. **Visualize actual vs predicted sales**

---

## 📊 Model Evaluation

| Metric      | Value | Meaning                                                                 |
|-------------|--------|-------------------------------------------------------------------------|
| **R² Score** | 0.91   | ✅ Explains **91%** of the variation in sales — excellent model fit.    |
| **MAE**      | 1.21   | 📉 Average error is ~**1.21 units** (in thousands).                     |
| **MSE**      | 2.29   | 🎯 Average squared error — penalizes large mistakes.                    |
| **RMSE**     | 1.51   | 📏 Average deviation of ~**1.51 units** in predictions.                 |

---

## 📌 Conclusion

- The model is **highly accurate and reliable**.
- It is well-suited for predicting sales based on ad spend.
- Future improvements could include:
  - Polynomial or Ridge regression
  - Removing weaker features like Newspaper
  - Trying ensemble models for comparison

---

## 🧠 Author

- **Name:** Yashvant Bendre
- **Learning Stage:** Practicing regression models (Simple & Multiple)
- **Goal:** Strengthen foundation in machine learning and data science

---



