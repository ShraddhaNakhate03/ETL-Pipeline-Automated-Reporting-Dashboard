# 📊 ETL Pipeline & Automated Reporting Dashboard

## 🔍 Project Overview
Built an end-to-end **ETL pipeline** to transform messy e-commerce transaction data into a clean, analysis-ready dataset and automated reporting dashboard.

This project replicates a **real-world business scenario** where manual reporting was inefficient and data quality issues impacted decision-making.

---

## 🎯 Business Problem
A UK-based e-commerce company faced:
- Poor data quality (duplicates, cancellations, missing values)
- No structured data model
- 3 days/month spent on manual reporting

---

## 🎯 Objective
- Build a scalable **ETL pipeline**
- Clean and transform raw transactional data
- Automate reporting using Power BI
- Enable faster, data-driven decisions

---

## 🛠️ Tech Stack (ATS Keywords 🚀)
- **Python (Pandas, pandasql)**
- **SQL (SQLite)**
- **Power BI**
- **ETL Pipeline Development**
- **Data Wrangling & Data Cleaning**
- **Alteryx (Conceptual ETL Mapping)**

---

## ⚙️ ETL Pipeline Architecture

1. **Extract**
   - Raw dataset: 541,909 records
   - Identified 5 major data quality issues

2. **Transform (Data Wrangling)**
   - Removed:
     - Cancelled orders
     - Negative quantities
     - Null Customer IDs
     - Zero unit prices
     - Duplicates
   - Clean dataset: 387,024 records

3. **Feature Engineering**
   - Revenue
   - Month, Year, Quarter
   - Customer Type
   - Revenue Band
   - Country Group

4. **Load**
   - Structured into **SQLite database**
   - Designed **normalized schema (4 tables)**

---

## 📊 Dashboard Preview



<img width="1336" height="747" alt="Revenue Overview" src="https://github.com/user-attachments/assets/e6ec05a7-e07e-45e5-a861-b7bb2005d5f7" /></br>
</br>

<img width="1327" height="744" alt="Product Analysis" src="https://github.com/user-attachments/assets/7f567703-bf26-4207-9893-b97121439379" />


---

## 📈 Key Insights (Deloitte-Style Storytelling)

- 🚨 **28.5% data was unusable** → Major data quality risk identified  
- 🇬🇧 **UK contributes 84% revenue** → Strong domestic dependency  
- ❌ **23% cancellation rate** → Operational inefficiency  
- 🛍️ Top product drives repeat purchases → Revenue concentration risk  
- 📅 **Q4 generates 40%+ revenue** → Strong seasonality trend  

---

## 💡 Business Impact

- ⏱️ Reduced reporting time from **3 days → Instant dashboard**
- 📊 Enabled **real-time decision making**
- 🧹 Improved **data reliability & trust**
- 📉 Identified revenue leakage due to cancellations

---

## 🧠 Key Learnings

- Importance of **data quality in analytics**
- Hands-on experience in **ETL pipeline design**
- Practical implementation of **data wrangling techniques**
- Building **business-ready dashboards**

---

## 🔗 Future Improvements

- Integrate real-time data pipeline (Airflow / APIs)
- Deploy dashboard to Power BI Service
- Implement anomaly detection for cancellations

---

## 📬 Contact
🔗 LinkedIn: linkedin.com/in/shraddhanakhate29  
💻 GitHub:  github.com/ShraddhaNakhate03  

---

⭐ If you found this useful, give it a star!
