# Power BI Project: Hospital Management Analysis

## Problem Statement
Analyze hospital management data (patients, doctors, appointments, treatments, billing) to create an interactive dashboard that provides insights into hospital operations, doctor performance, and revenue.

## Tools Used
- Power BI (Power Query, Data Modeling, DAX, Visualizations)

## Analysis Steps
1. Imported 5 tables (patients, doctors, appointments, treatments, billing) into Power BI.
2. Used Power Query to clean and verify data types.
3. Created Relationships (One-to-Many) between tables:
   - patients + appointments (patient_id)
   - doctors + appointments (doctor_id)
   - appointments + treatments (appointment_id)
   - patients + billing (patient_id)
4. Created DAX Measures:
   - Total Patients
   - Total Doctors
   - Total Appointments
   - Total Revenue
   - Avg Revenue per Patient
5. Built visualizations:
   - Cards (Total Patients, Total Doctors, Total Revenue)
   - Pie Chart (Gender Distribution)
   - Bar Chart (Doctor Specializations)
   - Column Chart (Appointments by Date)
   - Bar Chart (Treatments)
6. Assembled a comprehensive Dashboard.

## Key Results
- Total patients: [الرقم اللي طلع]
- Total doctors: 10
- Total Revenue: [الرقم اللي طلع]
- Appointments show distribution across different dates.
- Doctors are distributed across specializations.

## Files
- `Data/` – 5 CSV files.
- `PowerBI/` – Power BI file (.pbix).
- `Screenshots/` – Images of all visualizations.

## Author
Sarah Fayez – Medical Student & Data Analyst