# 📊 Customer Retention & Churn Analysis
### Future Interns – Data Science & Analytics | Task 2 (2026)

---

## 📌 Objective
Analyze customer data to identify churn patterns, key retention drivers,
and customer lifetime trends for a subscription-based business.

---

## 🛠️ Tools Used
- **Python (Pandas)** – Data cleaning and exploratory analysis
- **Tableau Public** – Interactive dashboard creation

---

## 📁 Dataset
- **Source:** Telco Customer Churn Dataset (Kaggle)
- **Size:** 7,032 rows after cleaning
- **Key columns:** Customer ID, Gender, Senior Citizen, Tenure,
Contract, Payment Method, Monthly Charges, Churn

---

## 📈 Dashboard Preview
![Dashboard](dashboard.png)

---

## 🔍 Key Insights
- Overall churn rate is **26.58%** — 1,869 out of 7,032 customers churned
- **Month-to-month** contract customers churn the most (1,655 churned)
- **Two year** contract customers have the lowest churn — long contracts improve retention
- **Fiber optic** internet service has significantly higher churn than DSL
- **Electronic check** payment method has the highest churn (1,071 churned)
- Customers with **0-12 months tenure** churn the most — early retention is critical
- Churned customers pay **higher average monthly charges** (~$74) vs retained (~$61)

---

## 📂 Files in this Repository
| File | Description |
|------|-------------|
| `churn_analysis.ipynb` | Python notebook for data cleaning and EDA |
| `churn_cleaned.csv` | Cleaned and processed dataset |
| `dashboard.png` | Tableau dashboard screenshot |

---

## 🎯 Recommendations
- Offer discounts to convert month-to-month customers to annual contracts
- Investigate why Fiber optic customers churn more — service quality issues?
- Target new customers (0-12 months) with loyalty programs
- Review pricing for customers using Electronic check payment

---

## 🎓 Skills Demonstrated
- Data cleaning and preprocessing
- Customer churn and retention analysis
- KPI analysis and insight generation
- Dashboard design in Tableau
