

# 🏨 Atliq Hotels – Exploratory Data Analysis (EDA) Project

## 📌 Project Overview
Atliq Hotels, a leading hotel chain, has experienced a decline in revenue and occupancy in recent months.  
The objective of this project is to perform **Exploratory Data Analysis (EDA)** to uncover booking trends, identify operational inefficiencies, and recommend data-driven strategies for revenue recovery.

---

## 🎯 Objectives
- 📊 Understand booking trends across channels and regions.  
- 🏙️ Identify underperforming cities, hotel types, and room categories.  
- 🔄 Compare third-party platform performance with direct bookings.  
- ⚙️ Detect operational inefficiencies and pricing issues.  
- 💡 Recommend strategies to improve revenue and regain market share.

## 🔧 **ETL – Extract, Transform, Load**

### 1️⃣ **Extract**
- 📥 Pull data from the original booking database (including third-party inputs).  
- 🗄️ Store it in a staging environment for processing.  

### 2️⃣ **Transform**
- 🧹 Handle missing values (imputation/removal).  
- 🗓️ Convert incorrect data types (dates, numeric formats).  
- 🔄 Normalize data (e.g., city names, hotel types).  
- 📊 Aggregate and restructure tables for analysis readiness.  
- 🧮 Apply business logic (categorize bookings, calculate revenue).  

### 3️⃣ **Load**
- 💾 Load cleaned and transformed data into an analytical database/data warehouse.  
- ✅ Establish a **single source of truth** for reporting and BI.  

---

## 📂 Dataset Information
- **Files Used**: `dim_date`, `dim_hotels`, `dim_rooms`, `fact_aggregated_bookings`, `fact_bookings`, `new_data_august`
- **Time Period Covered**: May–August
- **Key Metrics**: Occupancy %, ADR, RevPAR, Revenue Generated, Revenue Realized
