# 🛒 eCommerce Customer Behavior Analysis

This project analyzes customer transactional data from an eCommerce platform to uncover behavioral insights and patterns. It showcases practical data analytics skills including cleaning, exploration, behavioral analysis, and visualization.

---

## 📊 Objectives

- Understand customer purchase behavior
- Analyze trends in product sales, returns, and churn
- Segment customers for targeted marketing
- Demonstrate skills in pandas, matplotlib/seaborn, and storytelling with data

---

## 🧹 Data Overview

- **250,000** customer transactions
- Fields include: Purchase Date, Product Category, Price, Quantity, Returns, Payment Method, Age, Gender, Churn, etc.
- Missing values handled and cleaned
- **Returns Column Handling**

- The `Returns` column originally had ~19% missing values.
- Based on observed values (0.0 and 1.0), missing entries were interpreted as "no return" and filled with 0.
- This makes the feature usable for modeling customer behavior and understanding return rates.


---

## 🔍 Key Analyses

- **Time Series Revenue Trends**
- **Customer Demographics (Age, Gender)**
- **Product Category Popularity**
- **Return Behavior by Gender and Age**
- **Churn Insights**

---

## Behavioral Modeling 

- RFM Analysis (Recency, Frequency, Monetary)
- Customer Segmentation
- Churn Prediction
### 🧠 RFM Analysis

Customers were segmented based on:
- **Recency**: Days since last purchase
- **Frequency**: Total purchases made
- **Monetary**: Total amount spent

This enabled grouping into:
- "Best Customers"
- "Recent Buyers"
- "Frequent Buyers"
- "Big Spenders"

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `ecommerce_behavior_analysis.ipynb` | Jupyter notebook with full analysis |
| `ecommerce_data.csv` | Original dataset |
| `README.md` | Project summary and structure |

---

## 🚀 Future Enhancements

- Build an interactive dashboard using Plotly or Dash
- Apply machine learning for churn prediction
- Automate monthly reporting

---

## 🙋‍♀️ Author

**Daphine Lucas**  
_Data Analyst | Data Storyteller | GitHub:Daphine Lucas

---


