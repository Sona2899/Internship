# 🛒 Supermart Grocery Sales – Retail Analytics & Profit Prediction

## 📌 Project Overview
This project analyzes retail transaction data from a Supermart grocery chain to uncover sales trends, profitability drivers, and seasonal patterns.  
The objective is to perform end-to-end exploratory data analysis (EDA) and build a machine learning model to predict profit, enabling data-driven business decisions related to pricing, discounts, and inventory planning.

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Analysis Performed
- Data cleaning and preprocessing
- Handling missing values and invalid dates
- Feature engineering from order date (month, day, weekday, weekend, quarter-end)
- Exploratory Data Analysis (EDA)
- Category-wise and city-wise sales analysis
- Monthly and seasonal sales trends
- Discount vs profit relationship analysis
- Correlation analysis between numerical variables

---

## 🤖 Machine Learning Approach
- **Target Variable:** Profit
- **Model Used:** Random Forest Regressor
- **Validation Strategy:** TimeSeriesSplit (to avoid data leakage)
- **Preprocessing Pipeline:**
  - Numerical features: Median imputation + Standard scaling
  - Categorical features: Mode imputation + One-hot encoding
- **Evaluation Metrics:**
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

## 🔍 Key Insights
- Sales volume and discount percentage are strong predictors of profit
- Certain product categories consistently generate higher sales
- Weekend and seasonal patterns influence revenue and profitability
- Excessive discounts can negatively impact profit margins
- Time-aware validation provides realistic model performance estimates

---

## 💡 Business Recommendations
- Optimize discount strategies to balance sales growth and profitability
- Focus inventory planning on high-performing categories
- Increase stock levels during high-demand months and weekends
- Monitor category-level profitability instead of sales alone
- Use predictive insights to support pricing and promotional decisions

---

## 📂 Dataset Information
- **Source:** Supermart Grocery Sales – Retail Analytics Dataset
- **Records:** Transaction-level grocery sales data
- **Key Columns:** Order Date, Category, Sub Category, City, Region, Sales, Discount, Profit

---

## 🚀 Project Outcome
- Built a complete data analytics pipeline from raw data to business insights
- Developed a robust machine learning model with time-series validation
- Delivered actionable recommendations for retail business optimization

---

## 📌 Next Steps (Future Enhancements)
- Experiment with advanced models (XGBoost, Gradient Boosting)
- Perform customer segmentation using clustering
- Build interactive dashboards using Power BI or Tableau
- Extend analysis to time-series forecasting

---

## ✅ Status
✔ Project Completed  

