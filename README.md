# 🏥 Hospital Waitlist Monitoring Dashboard – Power BI
![image](https://github.com/user-attachments/assets/4efab7bd-8ee3-4d2c-98aa-fa7744b0f6dd)


## 📌 Overview

This project presents a Power BI dashboard built to monitor hospital waitlist data from 2018 to 2021 across inpatient, outpatient, and day case services. The dashboard was designed to help healthcare administrators and analysts gain operational visibility into backlog trends, patient demographics, and specialty performance.

---

## 🎯 Objective

- Track hospital waitlist trends over time  
- Break down waitlists by specialty, age profile, and time band  
- Enable proactive decision-making through live metrics

---

## 📊 Key Features

- KPI Cards: Current vs. Previous Year Waitlist  
- Case Type Split: Donut chart by Inpatient / Day Case / Outpatient  
- Age Profile x Time Band Matrix  
- Specialty Breakdown & Top 5 Specialties  
- Interactive date and case type filters  
- Trend analysis over 3+ years

---

## 🧰 Tools Used

- Power BI (DAX & Visualization)
- Power Query (M Language)  
- Excel for initial data cleaning

---

## 🛠️ Development Process
This project followed a rigorous end-to-end data development workflow to transform raw hospital waitlist records into a clean, analyzable dataset that powers strategic healthcare insights.

📦 Data Sourcing & Consolidation
Collected real-world NHS waitlist data across two key categories: Inpatient and Outpatient, spanning 2018 to 2021.

Each category came in four separate .csv files (one per year).

Used Power Query to dynamically combine the files in each folder into consolidated Inpatient and Outpatient datasets.

🧹 Data Cleaning & Standardization
Performed data cleaning in Power Query:

Renamed columns for clarity and consistency.

Fixed data types across date, text, and numeric fields.

Created a custom Case_Type column in the Outpatient file to align schemas for downstream merging.

Combined the cleaned datasets into a unified table (All_Data) containing all records from 2018–2021.

Normalized Age_Profile and Time_Band values by trimming whitespace and handling nulls.

🧩 Dimensional Modelling
Integrated a Specialty_Dimension lookup table (from a separate .csv) to categorize clinical specialties into logical groups.

Established relationships between All_Data and Specialty_Dimension using the Specialty field to enable multi-dimensional analysis.

📊 Report Design & Insight Layer
Designed an interactive Power BI report with:

Custom DAX measures for dynamic calculations (e.g., latest month, previous year, percent change).

Bookmarks and slicers to filter by archive date, case type, specialty, age profile, and time band.

Drill-down dashboards including:

Waitlist trends over time

Specialty breakdowns

Age vs time analysis

Case-type comparisons

---

## 🔍 Use Cases
The dashboard would help to:
- Identify specialties with persistent backlog  
- Filter by time bands to spot long-waiting patient segments  
- Analyze which age groups are most impacted  
- Enable leadership teams to prioritize high-wait areas

---

## 📸 Dashboard Preview

![image](https://github.com/user-attachments/assets/b44bfd5d-fc9e-49fc-8b01-c3cdd2eacaf0)

![image](https://github.com/user-attachments/assets/1e132a0d-97ae-4d50-9b09-ff20dcc5db9a)

![image](https://github.com/user-attachments/assets/9dc6aaac-1f49-4883-ac54-1121ed6a445c)

## 🎯 Insights
Waitlist Growth: The total number of patients on the waitlist increased by 10.8% YoY, growing from 640K to 709K by the final reporting month. Outpatient cases accounted for 72.5% of all cases—highlighting potential pressure on ambulatory care services.

Case Type Analysis:

Outpatient cases dominated the list, followed by day cases and inpatient admissions.

Visual trends revealed a consistent rise in outpatient volumes post-2020, possibly due to backlogs from the pandemic.

Backlog Severity by Time and Age:

The 18+ months wait band had the highest volume of cases (303 patients), with a notable proportion being 16–64 year-olds, suggesting workforce impact.

Age groups 0–15 and 65+ showed moderate delays but were not as backlogged as the working-age population.

Top Specialties:

Paediatric Dermatology, ENT, Orthopaedics, and Emergency Medicine emerged as the top 5 specialisms with the longest waitlists.

Across all specialties, General, Bones, and Urinary systems had the highest volumes, pointing to consistent operational pressure in those areas.

Specialty Breakdown:

A detailed grid view allowed deep dives by specialty, age group, and time band—enabling targeted backlog reduction strategies.

## 💡 Strategic Recommendations
Prioritize investment in outpatient service capacity, particularly in general practice and orthopaedics.

Develop specialty-specific backlog clearance plans focusing on high-volume areas (e.g., General and Bone specialties).

Introduce wait time escalation triggers by age group and duration to ensure vulnerable patients are not overlooked.



---

## 👩🏽‍💻 Author

**Adepeju Esther Shittu**  
Business Data Analyst | Power BI | Strategy | Process Optimization  
[Portfolio](https://myfol.io/adepejushittu) | [LinkedIn](https://www.linkedin.com/in/adepejushittu)
