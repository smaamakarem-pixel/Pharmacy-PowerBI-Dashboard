# Pharmacy Power BI Dashboard

A comprehensive Business Intelligence system built in **Power BI**, analyzing pharmacy operations across patient demographics, drug consumption, clinical insights, inventory, customer experience, and executive performance.

> **Note:** This is part of my ITI graduation project (Data Analytics Program). This repository contains the **6 Power BI dashboards**, which I personally designed and developed — including the data model, DAX measures, and visual design for all six pages.

## 📊 Dashboard Pages

### 1. Patient Demographics
Overview of patient population, age distribution, gender split, and chronic condition rates.
- KPIs: Total Patients (899), Average Age (50.28), Chronic Patients % (40.82%), Avg Monthly Visits (365)
- Visuals: Age group breakdown, gender distribution, patient trend over time

### 2. Drug Consumption
Tracks prescription volume and drug usage patterns across the patient base.
- KPIs: Total Prescriptions, Avg Prescriptions per Patient
- Visuals: Consumption trend by gender over time, top dispensed drugs, drug category breakdown (pivot table)

### 3. Clinical Insights
Analyzes diagnosis patterns and chronic disease trends.
- KPIs: Total Diagnoses, Chronic Patients %, Avg Monthly Visits
- Visuals: Chronic patient trend by month, diagnosis distribution (treemap)

### 4. Inventory Operations
Monitors stock levels, turnover, and dispensing activity to support inventory planning.
- KPIs: Total Drugs, Stock Turnover Rate, Current Remaining Stock, Total Quantity
- Visuals: Stock waterfall analysis, top dispensed drugs by inventory impact

### 5. Customer Experience
Explores patient behavior patterns relative to age, dosage, and diagnosis.
- KPIs: Avg Dose per Visit, Avg Monthly Visits
- Visuals: Age vs. monthly dispense amount (scatter analysis), diagnosis frequency by patient count

### 6. Executive Business
High-level summary view for business decision-making.
- Visuals: Prescription trend over time, diagnosis/month pivot summary, drug dosage form breakdown

## 🛠️ Tools & Skills Used

- **Power BI**: Star-schema data modeling, DAX measures, KPI cards with trend indicators, interactive slicers
- **Data Model**: Patient, Drug, Dispense, and Inventory fact/dimension tables linked via a dedicated measures table
- **Visualization Techniques**: Waterfall charts, treemaps, scatter plots, pivot tables, donut and area charts

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `Pharmacy_Dashboards(6).pbix` | Power BI file containing all 6 dashboard pages |
| `Dash_Images/` | Preview images of each dashboard page (pdf_dash_1.png – pdf_dash_6.png) |
| `6 Dashboards.rar` | Screen recording demo of the dashboards, showcasing interactive KPI indicators |
| `Pharmacy_Data.rar` | Source data and stored procedures used to build the data model |

---
*Part of the ITI Data Analytics Graduation Project*
