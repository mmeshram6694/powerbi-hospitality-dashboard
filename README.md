🏥 Power BI Healthcare Billing Dashboard | KPI & Cost Analysis
End-to-end Power BI dashboard with KPIs, cost trends, and DAX-powered insights for hospital billing and patient services

This interactive Power BI dashboard delivers actionable insights into hospital billing data, providing stakeholders with a complete view of cost distribution, insurance coverage, and procedure-level trends. It enables smarter financial and operational decisions in the healthcare environment.

🎯 Objective
To build a powerful analytics dashboard that allows hospital administrators and finance teams to monitor total billing, patient costs, and department-wise performance—enabling data-backed improvements in care delivery and cost efficiency.

🌟 Project Highlights
💰 KPI Cards: Total Billing, Out-of-Pocket, Insurance Coverage, Avg. Treatment Cost

🏥 Department & Procedure billing breakdown with % contribution

📍 City-wise billing trends using interactive maps

📆 Analysis by Diagnosis, Service Type (Emergency/Inpatient/Outpatient), and Day Type

🎯 Clean UI with slicers, tooltips, and drill-down capability

🛠️ Tech Stack Used
Power BI Desktop: Visualization, DAX measures, and relationship modeling

DAX: KPIs like % Department Contribution, Avg Cost per Patient, Insurance vs Out-of-Pocket

CSV Files: Data across billing, diagnosis, department, city, and calendar

Power Query: Data cleaning, merging, and transformation

🧩 Data Model Overview
Tables Used
📁 fact_billing, dim_date, dim_department, dim_diagnosis, dim_city, dim_procedure

Custom Measures Created
🧮 Total Billing, Avg Treatment Cost, Insurance Coverage %, Out-of-Pocket, % by Department/Procedure, Patient Satisfaction Score (if available)

📁 Project Structure
bash
Copy
Edit
📦 PowerBI-Healthcare-Billing-Dashboard
├── 📊 HealthcareDashboard.pbix
├── 📁 Datasets/
│   ├── fact_billing.csv
│   ├── dim_date.csv
│   ├── dim_department.csv
│   ├── dim_city.csv
│   ├── dim_diagnosis.csv
│   └── dim_procedure.csv
├── 📁 Screenshots/
│   ├── main_kpi_cards.png
│   ├── department_insights.png
│   ├── procedure_analysis.png
│   ├── city_map_view.png
├── 📄 README.md
📷 Screenshots
🧩 Dashboard Overview

🏥 Department Billing Insights

🧪 Procedure-Level Billing

🗺️ City Map View

🔍 Key Insights & Takeaways
Cardiology and Orthopedics drive over 50% of departmental billing—critical areas for cost optimization.

X-Ray, CT Scan, and MRI are the top-billed procedures, contributing to 60%+ of all procedure costs.

Over $1.13M in Out-of-Pocket costs, signaling gaps in insurance coverage or policy limitations.

Cities like Birmingham and Manchester generate the highest billing—likely due to larger facilities or patient volume.

Emergency & Inpatient dominate high-cost treatments like Fractures and Asthma, while Outpatient is preferred for Hypertension and Migraine.

🚀 Optimization Results
Created custom DAX measures for department/procedure-level % contribution

Enabled cross-filtering by service type and diagnosis for deeper exploration

Identified top 3 cost drivers by department and procedure

Added dynamic slicers for city, department, and date filters to refine exploration

📌 Business Recommendations
Review and renegotiate insurance terms for high Out-of-Pocket departments

Introduce bundled pricing for repeat procedures like X-Ray and CT Scan

Prioritize patient education and preventive outpatient care for chronic diagnoses

Evaluate underperforming procedures by realization rate and improve cost transparency

🧠 Learnings & Takeaways
💡 Developed complex KPIs and ratio-based metrics using DAX

🧩 Modeled a healthcare star schema with strong data relationships

📈 Improved storytelling with layered visuals and diagnosis-based trends

✅ Created a reusable dashboard framework for healthcare finance analytics

📬 Let’s Connect!
📧 mmeshram@umassd.edu
