

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

---

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


---

## 📂 Dataset Information
- **Files Used**: `dim_date`, `dim_hotels`, `dim_rooms`, `fact_aggregated_bookings`, `fact_bookings`, `new_data_august`
- **Time Period Covered**: May–August

---

## 🧪 EDA Process

### 📌 Data Cleaning
- Removed records where successful bookings exceeded hotel capacity.  
- Removed negative values in `no_guest` column.  
- Corrected unrealistic revenue values using **Three Sigma Rule**.  
- Handled outliers separately for expensive room category **RT4**.  

### 📌 Feature Engineering
- Created **OCC%** = `successful_booking / capacity`.  


### 📌 Analysis Performed
- **Occupancy % trends** by month, city, and room category.  
- **Revenue distribution** across platforms.  
- **Booking trends** across channels & regions.  
- **Outlier detection** for revenue metrics.  

---

## 📊 Key Insights
- 📉 Some cities and hotel types consistently underperform in occupancy.  
- 💰 Direct bookings generate higher revenue per booking compared to third-party platforms.  
- 🏷️ RT4 rooms are expensive but show stable performance with no extreme outliers.  
- 🕒 Clear seasonal patterns in booking volume — peak in July, drop in June.  

---

## 💡 Recommendations
- 🎯 Target marketing in low-performing cities.  
- 💻 Promote direct bookings with loyalty programs & exclusive discounts.    
- ⚙️ Monitor KPIs with automated Power BI dashboards for quick action.  

---

## 🛠️ Tools & Technologies
- 🐍 Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)  
- 📊 Power BI / Tableau for dashboarding  
- 📝 GitHub for version control and documentation  

