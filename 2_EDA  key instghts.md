## 🧪 EDA Process

### 📌 Data Cleaning
- Removed records where successful bookings exceeded hotel capacity.  
- Removed negative values in `no_guest` column.  
- Corrected unrealistic revenue values using **Three Sigma Rule**.  
- Handled outliers separately for expensive room category **RT4**.  

### 📌 Feature Engineering
- Created **OCC%** = `successful_booking / capacity`.  
- Calculated **ADR** (Average Daily Rate) and **RevPAR** (Revenue per Available Room).  

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
- 📈 Apply **dynamic pricing** to match seasonal demand.  
- ⚙️ Monitor KPIs with automated Power BI dashboards for quick action.  

---

## 🛠️ Tools & Technologies
- 🐍 Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)  
- 📊 Power BI / Tableau for dashboarding  
- 🗄️ SQL for data extraction & transformation  
- 📝 GitHub for version control and documentation 
