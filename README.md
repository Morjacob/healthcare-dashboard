# Healthcare Data Analytics Dashboard

## Project Overview
This project demonstrates a full **SQL + Python workflow** using a healthcare dataset. It showcases how raw patient data can be analyzed and visualized to generate actionable insights. 

The notebook combines:

- **SQL queries** for aggregating and summarizing data
- **Python (pandas & matplotlib)** for visualizations
- **KPI calculations** and dashboard-style charts

---

## Dataset
The dataset contains patient records with the following columns:

- `Name` – Patient name
- `Age` – Patient age
- `Gender` – Male/Female
- `Blood Type` – Patient blood type
- `Medical Condition` – Diagnosed conditions
- `Date of Admission` / `Discharge Date` – Hospital stay period
- `Doctor` – Assigned doctor
- `Hospital` – Hospital name
- `Insurance Provider` – Insurance company
- `Billing Amount` – Treatment cost
- `Room Number` – Assigned room
- `Admission Type` – e.g., Emergency, Routine
- `Medication` / `Test Results` – Prescribed treatment and lab tests

---

## Features & KPIs

1. **Total Patients** – Count of all patients  
2. **Average Age** – Mean patient age  
3. **Patients per Hospital** – Top hospitals by number of patients  
4. **Patients per Doctor** – Top 10 doctors by patient load  
5. **Average Billing per Insurance Provider** – Mean billing by insurance company  
6. **Age Distribution** – Histogram of patient ages  
7. **Top Medical Conditions** – Most common diagnoses  

---

## SQL Integration
The project uses **SQLite** to demonstrate SQL skills:

- CSV data is imported into a SQL table (`patients`)  
- Queries are run using `pandas.read_sql()`  
- Aggregations (`COUNT`, `AVG`) and groupings (`GROUP BY`) are executed in SQL  

This shows how SQL can be combined with Python for healthcare data analysis.

---

## Visualizations
- Bar charts: Patients per Hospital, Top Doctors, Top Medical Conditions  
- Histogram: Age distribution  
- Charts are fully interactive in Jupyter Notebook  

---

## How to Run
1. Clone the repository:

```bash
git clone <your-github-repo-url>
cd patient_analytics_demo
