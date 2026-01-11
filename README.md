# Intuit QuickBooks Upgrade Targeting Model

## 📌 Project Overview
This project focuses on identifying **high-potential small businesses** most likely to upgrade from a basic QuickBooks plan to a **higher-tier subscription**. The goal is to enable Intuit’s growth and marketing teams to move from blanket campaigns to **data-driven, targeted upgrade strategies**.

Using customer behavior, firmographics, and product usage data, we build a predictive targeting model to prioritize businesses with the highest upgrade propensity.

---

## 🎯 Business Problem
Intuit faces a common SaaS challenge:  
Not all customers have the same likelihood of upgrading, yet marketing efforts are often broad and inefficient.

**Key questions addressed:**
- Which businesses are most likely to upgrade their QuickBooks subscription?
- What customer attributes and behaviors drive upgrade decisions?
- How can Intuit optimize marketing spend and conversion rates?

---

## 📊 Data Description
The dataset includes:
- Business size and demographics
- Product usage metrics
- Subscription and engagement indicators
- Historical upgrade behavior

Key files:
- `to_target_businesses.csv` – customer-level dataset
- `intuit.ipynb / Intuit_analysis.ipynb` – exploratory analysis and modeling
- `intuit-quickbooks-case.pdf` – business case context

---

## 🔍 Methodology
1. **Exploratory Data Analysis**
   - Distribution analysis of business size, usage, and engagement
   - Identification of key behavioral patterns linked to upgrades

2. **Feature Engineering**
   - Creation of meaningful indicators from raw usage data
   - Normalization and preparation for modeling

3. **Predictive Modeling**
   - Classification approach to predict upgrade likelihood
   - Model comparison and evaluation using performance metrics

4. **Targeting Strategy**
   - Ranking customers by predicted upgrade probability
   - Segmenting customers into actionable marketing buckets

---

## 📈 Key Insights
- Product engagement intensity is a strong predictor of upgrade behavior
- Medium-sized businesses show higher upgrade propensity than very small firms
- A small subset of customers drives a disproportionate share of upgrade potential

---

## 💡 Business Impact
- Enables **precision marketing** instead of mass campaigns
- Improves expected conversion rates while reducing acquisition costs
- Supports revenue growth through smarter customer targeting
- Provides a scalable framework for future upsell and cross-sell strategies

---

## 🛠 Tools & Skills Used
- Python (Pandas, NumPy, Scikit-learn)
- Exploratory Data Analysis (EDA)
- Classification Models
- Customer Segmentation
- Business Analytics & Decision Making
- SaaS Growth & Monetization Strategy

---

## 📌 Conclusion
This project demonstrates how **customer analytics and predictive modeling** can directly support revenue growth in SaaS businesses by aligning marketing actions with customer behavior and value.
