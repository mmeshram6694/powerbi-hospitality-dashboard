# 🏥 Power BI Healthcare Billing Dashboard | KPI & Cost Analysis

This repository contains an end-to-end **Power BI dashboard** for healthcare billing analytics, featuring KPIs, cost trends, and DAX-powered insights for hospital billing and patient services. The interactive dashboard provides stakeholders with a comprehensive view of cost distribution, insurance coverage, and procedure-level trends—enabling smarter financial and operational decisions in the healthcare environment.

---

## 🎯 Objective

To build a powerful analytics dashboard that allows hospital administrators and finance teams to monitor total billing, patient costs, and department-wise performance—enabling data-backed improvements in care delivery and cost efficiency.

---

## 🌟 Project Highlights

- 💰 **KPI Cards:** Total Billing, Out-of-Pocket, Insurance Coverage, Avg. Treatment Cost
- 🏥 **Department & Procedure Billing:** Breakdown with % contribution
- 📍 **City-wise Billing:** Interactive map-based trends
- 📆 **Diagnosis & Service Type Analysis:** Emergency, Inpatient, Outpatient, and Day Type
- 🎯 **Clean UI:** Slicers, tooltips, and drill-down capability for seamless exploration

---

## 🛠️ Tech Stack Used

- **Power BI Desktop:** Visualization, DAX measures, and relationship modeling
- **DAX:** KPIs like % Department Contribution, Avg. Cost per Patient, Insurance vs Out-of-Pocket
- **CSV Files:** Data across billing, diagnosis, department, city, and calendar
- **Power Query:** Data cleaning, merging, and transformation

---

## 🔄 Project Workflow

### 1. Data Ingestion & Cleaning
- Handled data from multiple tables: `Billing`, `Patients`, `Procedures`, `Departments`, `Diagnosis`, `Date`  
- Cleaned nulls, corrected mismatches, standardized naming conventions  

### 2. Data Modeling
- Created a **Star Schema** with:  
  - Fact Table: `Billing`  
  - Dimension Tables: `Patients`, `Procedures`, `Departments`, `Diagnosis`, `Date`, `City`  

### 3. DAX-Driven KPI Development
- Measures created for:  
  - Total Billing, Insurance, Medication, Treatment, Room Charges, Out-of-Pocket  
  - Averages per patient: Billing, Insurance, Treatment, Medication, Room Charges  
  - % Share by Department and Procedure  
  - Patient Satisfaction & Length of Stay (if available)  

### 4. Dashboard Design
- Used bar, stacked bar, map, and KPI cards  
- Interactive filters: by City, Department, Procedure, and Service Type  
- Designed for high-level overview and detailed drilldowns  

---

## 📁 Project Structure

📦 PowerBI-Healthcare-Billing-Dashboard/
├── HealthcareDashboard.pbix
├── 📁 Screenshots/
│   ├── MainDashboard.png
├── 📄 README.md


---

## 📷 Screenshots

- **Dashboard Overview**
- **Department Billing Insights**


---

## 🔍 Key Insights & Takeaways

- **Cardiology and Orthopedics** drive over 50% of departmental billing—critical areas for cost optimization.
- **X-Ray, CT Scan, and MRI** are the top-billed procedures, contributing to 60%+ of all procedure costs.
- **Out-of-Pocket costs** exceed $1.13M, signaling gaps in insurance coverage or policy limitations.
- **Birmingham and Manchester** generate the highest billing—likely due to larger facilities or patient volume.
- **Emergency & Inpatient** dominate high-cost treatments like Fractures and Asthma, while **Outpatient** is preferred for Hypertension and Migraine.

---

## 🚀 Optimization Results

- Created custom DAX measures for department/procedure-level % contribution
- Enabled cross-filtering by service type and diagnosis for deeper exploration
- Identified top 3 cost drivers by department and procedure
- Added dynamic slicers for city, department, and date filters to refine exploration

---

## 📌 Business Recommendations

- Review and renegotiate insurance terms for high Out-of-Pocket departments
- Introduce bundled pricing for repeat procedures like X-Ray and CT Scan
- Prioritize patient education and preventive outpatient care for chronic diagnoses
- Evaluate underperforming procedures by realization rate and improve cost transparency

---

## 🧠 Learnings & Takeaways

- 💡 Developed complex KPIs and ratio-based metrics using DAX
- 🧩 Modeled a healthcare star schema with strong data relationships
- 📈 Improved storytelling with layered visuals and diagnosis-based trends
- ✅ Created a reusable dashboard framework for healthcare finance analytics

---

## 📬 Let’s Connect!

- **Email:** mmeshram@umassd.edu

> *Empowering healthcare leaders with data-driven insights for better care and smarter operations.*
