# Advertisement Budget Sales Prediction using linear regression

### 📌 Description  
A Linear Regression project to analyze and predict sales based on TV, Radio, and Newspaper advertisement budgets.

---

## 📁 Project Overview  
This project demonstrates how linear regression can be applied to a marketing dataset to determine the relationship between advertising spend and sales performance.

---

## 🧪 Key Features  
- Linear Regression using Scikit-learn  
- Data visualization with Seaborn and Matplotlib  
- Model evaluation using MAE, MSE, R² Score, and cross-validation  
- Outlier detection and comparison of model performance before and after removing outliers  

---

## 📊 Results Summary  

| Metric         | With Outliers | Without Outliers |
|----------------|----------------|-------------------|
| Accuracy (R²)  | 89.94%         | 87.82%            |
| MAE            | 0.28           | 1.39              |
| MSE            | 0.12           | 3.26              |

**Insights:**  
- TV and Radio have the strongest influence on sales.  
- Newspaper budget has minimal impact.  
- Removing outliers reduces accuracy slightly but offers more stable predictions.

---

## ✅ Model Usage Guidance

- **Use the one _without outliers_** when you want a **more stable and fair predictor**.
- **Use the one _with outliers_** when you're okay with **higher sensitivity but possible overfitting**.

---

## 📎 How to Run  
1. Clone the repository  
2. Open the Jupyter/Colab notebook  
3. Run all cells to view analysis and predictions  
