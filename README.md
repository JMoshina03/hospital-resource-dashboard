# Hospital Resource Utilization & Patient Outcomes Dashboard

## Overview
This project provides an **interactive Power BI dashboard** to monitor hospital resource utilization and patient outcomes. It helps management optimize **admissions, ICU demand, bed occupancy, doctor utilization, and revenue** across departments and branches.

---

## Problem Statement
Hospitals face challenges in effectively tracking **patient admissions, ICU requirements, bed usage, staff allocation, and revenue**. Without consolidated insights, decision-making can be slow and inefficient.

---

## Solution
This project uses **MySQL** and **Power BI** to create an interactive dashboard that visualizes hospital operations and key performance indicators (KPIs). Users can explore trends, compare departments, and optimize resource allocation.

---

## Tech Stack
- **Database:** MySQL  
- **Visualization:** Power BI  
- **Version Control:** GitHub  

---

## Key KPIs
- **Total Admissions** – Total number of patients admitted  
- **Average Length of Stay (ALOS)** – Average duration of hospitalization  
- **ICU Requirement %** – Percentage of patients requiring ICU care  
- **Readmission Rate** – Percentage of patients readmitted  
- **Total Revenue** – Revenue generated from admissions and treatments  
- **Bed Occupancy Rate** – Percentage of beds occupied  

---

## Dataset
All datasets are available in the `/dataset` folder:  
- `patients.csv` – Patient demographic details  
- `admissions.csv` – Admission and discharge information  
- `billing.csv` – Revenue and payment details  
- `doctors.csv` – Doctor assignments and schedules  
- `beds.csv` – Bed availability and occupancy  

---

## SQL
All database creation scripts, KPI queries, and views are included in `/sql/hospital_db.sql`.

---

## Dashboard
The **Power BI dashboard** visualizes KPIs and trends with **interactive slicers and drill-downs** for departments, time periods, and patient categories.

---

## Outcome
This dashboard enables hospital management to:  
- Optimize **staff allocation** and ICU usage  
- Monitor **bed occupancy** in real-time  
- Track **financial performance**  
- Improve **patient care** and reduce readmission rates  

---

## How to Run
1. Import CSV files into **MySQL** using `/sql/hospital_db.sql`.  
2. Connect **Power BI Desktop** to the MySQL database.  
3. Load the data and create relationships as defined in the SQL script.  
4. Open the **Power BI dashboard file** included in the repository.  

---

## Notes
- This dashboard is intended for **demo or educational purposes**.  
- **Sensitive hospital data should not be shared publicly**.
