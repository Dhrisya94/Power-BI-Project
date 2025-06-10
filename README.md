# Hospital Emergency Room (Interactive Dashboard creation using Power BI)
## Project Objective
To enhance operational efficiency and provide actionable insights into emergency room performance, we need to create a Hospital Emergency Room Analysis Dashboard in Power BI. This solution will enable stakeholders to track, analyze, and make data-driven decisions regarding patient management and service optimization.
## Data Set Used
<a href= "https://github.com/Dhrisya94/Power-BI-Project/blob/799e693bd641e7352fe3e29081f623453c3216c8/Hospital%20ER_Data.csv"> Dataset</a>

## STEPS IN PROJECT
Requirement Gathering/ Business Requirements

Data Walkthrough

Data Connection

Data Cleaning / Quality Check

Data Modeling

Data Processing

DAX Calculations

Dashboard Lay outing

Charts Development and Formatting

Dashboard / Report Development

Insights Generation


## KPI’s Requirements

Number of Patients:
Measure the total number of patients visiting the ER daily.
Display a daily trend using an area sparkline to understand patterns over time, such as peak days or seasonal trends.

Average Wait Time:
Calculate the average time patients wait before being attended to by a medical professional.
Use an area sparkline to show daily fluctuations and identify days with higher wait times that may require operational adjustments.

Patient Satisfaction Score:
Analyze the average satisfaction score of patients on a daily basis to evaluate the quality of service provided.
Present a daily trend using an area sparkline to identify dips in satisfaction and correlate them with operational challenges or peak times.

Number of Patients Referred:
Count the number of patients referred to specific departments from the ER each day.
Use an area sparkline to track daily trends and identify departments with high referral rates, which may require additional resources.

- Dashboard Interaction <a href= "https://github.com/Dhrisya94/Power-BI-Project/blob/main/Hospital%20emergency%20room.pbix">DASHBOARD VIEW</a>

## Dashboard 1: Monthly View 
Objective: Monitor key metrics and trends on a month-by-month basis to identify patterns and areas for improvement.

Charts to Develop:

Patient Admission Status: Track admitted vs. non-admitted patients.

Patient Age Distribution: Group patients by 10-year age intervals.

Department Referrals: Analyze referral trends across different departments.

Timeliness: Measure the percentage of patients seen within 30 minutes.

Gender Analysis: Visualize patient distribution by gender.

Racial Demographics: Analyze patient data by race.

Time Analysis: Assess patient volume by day and hour.

-Dasboard View <a href="https://github.com/Dhrisya94/Power-BI-Project/blob/main/Monthly%20view.png">MONTHLY VIEW</a>

## Dashboard 2: Consolidated View 
Objective: Provide a holistic summary of hospital performance for a selected date range.

Charts to Develop:
Similar metrics as the Monthly View, but aggregated over a customizable date range for broader insights and trend analysis

- Dashboard View <a href="https://github.com/Dhrisya94/Power-BI-Project/blob/main/consolidated%20view.png">CONSOLIDATED VIEW</a>

## Dashboard 3: Patient Details
Objective: Offer granular insights into patient-level data to enable detailed analysis and troubleshooting.

Charts to Develop: A grid displaying essential fields:

Patient ID,
Patient Full Name,
Gender,
Age,
Admission Date,
Patient Race,
Wait Time,
Department Referral,
Admission Status,

-Dashboard view <a href="https://github.com/Dhrisya94/Power-BI-Project/blob/main/Patient%20details.png">PATIENT DETAILS</a>

# INSIGHTS

Descriptive Analysis
(April 2023-October 2024)

The emergency room dataset, covering a period of 19 months, records a total of 9,216 unique patients.

Patient Wait Time & Satisfaction:
The average wait time was approximately 35.3 minutes, indicating a need for improvement to enhance patient flow. The average satisfaction score was 4.99 out of 10.

Departmental referrals:
A significant number of patients(5400) did not required referrals. Among those referred, the most common were General Practice(1840 cases) and Orthopaedics (995 cases), followed by Physiotherapy(276 Cases) and Cardiology (248 Cases)

Peak busy Periods:
The busiest day were Saturdays(1377), Thursdays(1332) and Mondays(1314). The busiest hours were 11AM, 7PM, 01PM and 11PM indicating need of a ample staffing during these periods.

Patient Demographics:
Age Groups: Adults(30-39 Years) formed a large group(1200 patients), followed by young adults(20- 29 Years) with 1188 Patients. Other significant groups included middle aged as well(40-50 Years).

Race Distribution:
The largest racial group was White(2571), followed by African American(1951) multi racial(1557) and Asian (1060) patients. A significant number of patients(1030) declined to identify their race.

Admission Patterns:
Nearly half of the patients (4612) were admitted, while the rest (4604) were treated and released.

## Summary:
The dataset reveals high patient volumes, moderate satisfaction levels, and common referrals to General Practice and Orthopaedics. Saturdays and late night to early mornings hours are particularly busy. The patient demographics show a diverse age and racial composition, with nearly equal number of admitted and not admitted patients. These insights can help optimize resource allocation and improve patient care in the emergency room.












