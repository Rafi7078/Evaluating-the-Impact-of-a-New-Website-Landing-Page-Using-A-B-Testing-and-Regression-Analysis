# 📊 A/B Testing & Logistic Regression Analysis

## 📌 Project Overview
This project analyzes an A/B test conducted on an e-commerce landing page to determine whether a new page improves user conversion rates compared to the existing page.

The analysis combines:
- A/B testing (statistical hypothesis testing)
- Logistic regression modeling
- Exploratory data analysis
- Time and country-based segmentation

---

## 🎯 Objective
To determine whether the new landing page significantly improves conversion rate and whether external factors (country, time, weekday) influence user behavior.

---

## 📂 Dataset Description

### 1. A/B Testing Data
- user_id
- timestamp
- group (control/treatment)
- landing_page
- converted

### 2. Country Data
- user_id
- country

---

## 🧪 Methodology

- Data Cleaning
- Feature Engineering
- Conversion Rate Analysis
- Sample Ratio Mismatch Test
- Two-Proportion Z-Test
- Confidence Interval Estimation
- Simulation-Based Testing
- Logistic Regression Modeling
- Interaction Analysis

---

## 📊 Key Results

- Control conversion rate: ~12.04%
- Treatment conversion rate: ~11.88%
- Difference: -0.16 percentage points
- No statistically significant improvement detected
- Logistic regression confirms no meaningful uplift

---

## 📉 Key Visualizations

- Group allocation distribution
- Conversion rate comparison
- Country-wise performance
- Time-based conversion trends
- ROC curve analysis

---

## 🧠 Final Conclusion

The new landing page does NOT significantly improve conversion rate.  
The existing page should be retained.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Statsmodels
- Google Colab

---

## 📁 Project Structure

See repository folders for detailed breakdown.

---

## 👨‍💻 Author

Data Analyst / QA & Analytics Enthusiast
