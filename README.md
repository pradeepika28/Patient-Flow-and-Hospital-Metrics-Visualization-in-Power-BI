# Healthcare Billing Analytics Dashboard Using Power BI
## Project Overview
This project is an interactive Power BI dashboard designed to analyze healthcare billing data across multiple dimensions such as departments, procedures, diagnoses, and service types. It leverages DAX (Data Analysis Expressions) to create custom measures and calculated fields, providing actionable insights and enhancing decision-making capabilities in healthcare financial management.
## Key Features
### 1. Billing Analysis
- **Total Billing by Department:** Visualizes billing amounts with the percentage of each department's contribution to the grand total.
- **Total Billing by Procedure:** Provides detailed insights into billing distribution by different medical procedures, including their percentage contributions.
- **Diagnosis and Service Type Breakdown:** Presents comprehensive billing analysis segmented by medical diagnoses and service types.
### 2. KPI Tracking
Tracks critical Key Performance Indicators including:
- Billing Amount
- Medication Cost
- Treatment Cost
- Total Insurance Covered
- Room Charges
- Out-of-Pocket Expenses
Calculates and visualizes the averages for each KPI, supporting better budget management and financial forecasting.
### 3. Time Based Analysis
Includes a dynamic date dimension table (Datetable) for robust time-series analysis, allowing tracking of trends over different periods:
- Daily
- Weekly
- Monthly
- Quarterly
- Yearly
- Weekday/Weekend classification
## DAX Measures Created:
- **Averages and Totals for KPIs:** Created measures to calculate total and average values for Billing Amount, Medication Cost, Treatment Cost, Insurance, Room Charges, and Out-of-Pocket.
- **Date Table Enhancements:** Custom Datetable includes calculated columns for Year, Month, Quarter, Weekday, and classification as Weekday/Weekend.
- **% Calculations:**
  - **% Department:** Calculates percentage contribution of each department.
  - **% Procedure:** Determines the percentage of billing by medical procedure.
- Active Department: Identifies selected department contextually using SELECTEDVALUE().
## Tools and Technologies:
- Power BI Desktop
- DAX (Data Analysis Expressions)
