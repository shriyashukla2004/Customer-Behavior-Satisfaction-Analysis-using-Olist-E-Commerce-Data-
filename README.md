# 🛒 Olist E-Commerce Customer Analytics

## 📌 Overview
This project analyzes the Olist Brazilian E-Commerce dataset to understand customer purchasing behavior, delivery performance, payment trends, and regional satisfaction patterns.

Using SQL, Python, and Power BI, the project combines exploratory data analysis, statistical testing, and interactive dashboards to uncover business insights and support data-driven decision-making.

---

# 🚀 Tech Stack
- SQL Server
- Python
- Pandas & NumPy
- SciPy & StatsModels
- Power BI
- Matplotlib & Seaborn

---

# 📂 Dataset
The dataset contains:
- 100K+ e-commerce orders
- Customer and seller information
- Product details
- Payment data
- Delivery timestamps
- Customer reviews
- Geolocation data

Source: Olist Brazilian E-Commerce Public Dataset (Kaggle)

---

# ⚙️ Workflow
- Data Cleaning & Preprocessing
- SQL Querying & Table Joins
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Statistical Hypothesis Testing
- Dashboard Development in Power BI
- Business Insight Generation

---

# 📊 Key Insights

- Credit card users showed significantly higher transaction values compared to other payment methods.
- Delivery delays were generally associated with lower customer review scores.
- Some regions maintained good review scores despite longer delivery durations, suggesting regional expectations influence customer satisfaction.
- A small group of sellers contributed a major share of marketplace revenue.
- Categories related to beauty, home, and lifestyle generated comparatively higher revenue.

---

# 📈 Statistical Analysis

## Hypothesis 1
### Customers Paying via Credit Card Spend More Than Customers Using Other Payment Methods

### Tests Used
- One-Way ANOVA
- T-Test
- Regression Analysis

### Result
The statistical analysis confirmed that payment methods significantly influence transaction value, with credit card users showing noticeably higher spending behavior.

---

## Hypothesis 2
### Customer Satisfaction Is Influenced More by Regional Expectations Than by Delivery Speed Alone

### Test Used
- One-Way ANOVA

### Result
The analysis suggested that customer satisfaction varies across regions even after considering delivery duration and freight costs, indicating that customer expectations and regional perception also influence review behavior.

---

# 📊 Dashboards

The project includes interactive Power BI dashboards covering:
- Business Performance Overview
- Customer Experience & Delivery Analysis
- Seller & Customer Insights

---

# 💡 Recommendations

- Promote credit card offers and cashback campaigns for high-value customer segments.
- Improve delivery communication through accurate ETAs and proactive shipment updates.
- Implement region-specific customer experience strategies based on delivery expectations and regional behavior patterns.

---

# 🔍 Future Scope

Future analysis can explore:
- Customer retention modeling
- Churn prediction
- Customer lifetime value (CLV)
- Cohort analysis
- Repeat purchase behavior

---

# 📁 Project Files

```bash
Olist_Data_Analysis.ipynb
EDA_Hypothesis.sql
PowerBI_Dashboard.pbix
README.md
