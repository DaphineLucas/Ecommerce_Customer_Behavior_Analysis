# 🛒 eCommerce Customer Behavior Analysis

This project analyzes customer transactional data from an eCommerce platform to uncover behavioral insights and patterns. It showcases practical data analytics skills including cleaning, exploration, behavioral analysis, and visualization.

---

## 📊 Objectives

- Understand customer purchase behavior
- Analyze trends in product sales, returns, and churn
- Segment customers for targeted marketing
- Payment preferences to uncover actionable business insights
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

---
| Area                   | Description                                                            |
| ---------------------- | ---------------------------------------------------------------------- |
| 📦 Data Cleaning       | Removed nulls, renamed columns, typed conversions                      |
| 🔎 EDA                 | Univariate, bivariate, and multivariate visualizations                 |
| 🧠 Feature Engineering | Added age groups, spending segments, return rate, customer types, etc. |
| 📉 Churn Analysis      | Explored churn by age, gender, weekday, return rate, spending          |
| 📊 Visualization       | Used Seaborn & Matplotlib for business-friendly insights               |

### 🔍 Model Comparison Summary (Initial)

| Model               | Accuracy | Notes |
|--------------------|----------|--------|
| Logistic Regression | ~79% | Moderate accuracy, better than decision tree on recall |
| Decision Tree       | ~80% | High overall accuracy, but very poor at predicting churn |
| Issue               | Class Imbalance | Tree model predicts non-churners (0) almost always |
| Next Steps          | Resampling, class weights, Random Forest |

## 🛠️ Tools Used
- **Python**, **Jupyter Notebook**
- **Pandas**, **Matplotlib**, **Seaborn**, **Scikit**
- **Git**, **GitHub**

---

## 🚀 How to Run
1. Clone the repository
2. Open the notebook in Jupyter
3. Run all cells to reproduce analysis


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


