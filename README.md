# 🏭 FMCG Supply Chain KPI Analysis – Power BI

## ⚙️ Tools Used
Power BI | DAX | Power Query | Data Modeling | Excel  

---

## 📌 Project Overview

This project analyzes supply chain performance for AtliQ Mart, an FMCG manufacturer facing delivery reliability issues.

The dashboard tracks **On-Time (OT%)**, **In-Full (IF%)**, and **On-Time In-Full (OTIF%)** to identify operational gaps across cities, customers, and products.

---

## 🧠 Business Objective

- Monitor delivery performance vs targets  
- Identify underperforming cities & customers  
- Analyze monthly trends  
- Improve order-level fulfillment  

---

## 📊 Key Insights

- **OTIF% = 47.95%**, ~18% below the 65.91% target — indicating systemic execution gaps.  
- **Ahmedabad performs best**, while **Surat & Vadodara** show recurring underperformance (especially June–July).  
- Customers like **Coolblue** and **Acclaimed Stores** have OTIF below 20%, creating churn risk.  
- **Volume Fill Rate (~96.6%) is strong**, but **Line Fill Rate (~65.9%) is weak**, showing order completeness issues at SKU level.  
- Performance remains below target from March to August, suggesting structural inefficiencies.  

---

## 🗂️ Data Model & Approach

- Designed a **Star Schema** (Fact: Deliveries | Dimensions: Date, Customer, Product, City)  
- Built DAX measures for KPI %, variance, and trend tracking  
- Used Power Query for data cleaning & transformation  
- Enabled drilldowns by city, customer, and SKU  

---

## 🎯 Recommendations

- Improve SKU-level forecasting to increase line fill rate  
- Review logistics operations in Surat & Vadodara  
- Prioritize service recovery for low-OTIF customers  
- Introduce KPI alert thresholds for proactive monitoring  
