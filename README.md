# 🏨 Power BI Hospitality Dashboard | KPI & Trend Analysis
End-to-end Power BI dashboard with KPIs, trend insights, and DAX-based analytics for hospitality bookings

This interactive **Power BI dashboard** delivers end-to-end insights into key performance metrics in the **hospitality industry**. It empowers data-driven decision-making through dynamic visualizations of bookings, revenue, occupancy trends, and guest satisfaction.

---

## 📊 Dashboard Highlights

- 💰 **Total Revenue**: ₹1.69B  
- 📈 **Key KPIs**: ADR, RevPAR, Occupancy %, Realization %, Cancellation %, Average Rating  
- 🔁 **Comparative Analysis**:
  - Week-over-Week (WoW) % changes
  - Weekday vs Weekend performance
  - Business vs Luxury hotel performance
  - Booking platform comparison (logtrip, makeyourtrip, etc.)

---

## 🧩 Key Features

- 📅 Time Series Trend Analysis (by week no)
- 🏨 Hotel-wise KPI Breakdown
- 🛎️ Room Type & City Filters
- 🌐 Platform-wise Booking Insights
- 🧠 Advanced DAX Calculations (RevPAR, ADR, Realization %)
- 🔄 WoW Change Logic with `VAR` DAX formulas
- 🎯 Clean, modern UI with interactive slicers, KPIs, and conditional formatting

---

## 🗂️ Data Model Overview

**Tables Used**  
📁 `fact_bookings`, `fact_aggregated_bookings`  
📁 `dim_date`, `dim_hotels`, `dim_rooms`

**Custom Measures Created**  
🧮 Revenue, ADR, RevPAR, Occupancy %, Realization %, WoW % Changes, Avg Rating, Cancellation %

---

## 📷 Screenshots

> *(Insert dashboard visuals here — use light backgrounds for GitHub theme compatibility)*

---

## 📁 Project Structure

```bash
📦 PowerBI-Hospitality-Dashboard
├── 📊 HospitalityDashboard.pbix
├── 📁 Datasets/
│   ├── fact_bookings.csv
│   ├── fact_aggregated_bookings.csv
│   └── dim_*.csv
├── 📁 Screenshots/
├── 📄 README.md
