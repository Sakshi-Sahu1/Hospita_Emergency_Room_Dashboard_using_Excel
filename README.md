Hospital Emergency Room Data Analysis Dashboard
Project Overview
An interactive Excel dashboard for analyzing hospital emergency room operations, patient demographics, and department performance metrics. This project provides comprehensive insights into patient flow, wait times, satisfaction scores, and departmental referrals.

Data Description
The dataset contains 513 patient records with the following key attributes


Patient Information
Patient ID: Unique identifier (format: XXX-XX-XXXX)
Demographics: Gender, age, race/ethnicity
Admission Details: Date, time, department referral
Outcomes: Admission status, satisfaction score (0-10), wait time (minutes)


Key Metrics Tracked
Patient Volume: Total patients per month/department
Wait Times: Average 36.32 minutes
Satisfaction Score: Average 4.96/10
Admission Rate: ~47.5% of patients admitted
Demographics: Gender distribution (53% Female, 47% Male)


Dashboard Features
Main KPIs
Total monthly patients: 513
Average wait time: 36.32 minutes
Patient satisfaction: 4.96/10
Department breakdown with patient counts


Visualizations
Patient Age Distribution: Bar chart showing patient counts by age groups (0-9 through 70-79)
Patient Attendance Status: Pie chart (62% on-time, 38% delays)
Gender Analysis: Demographic breakdown
Department Referrals: Horizontal bar chart showing:
None: 299 patients
General Practice: 103 patients
Orthopedics: 65 patients
Cardiology: 14 patients
Physiotherapy: 14 patients
Neurology: 9 patients
Renal: 5 patients
Gastroenterology: 4 patients
Time Period Analysis
2023-2024 comparison toggle
Monthly breakdown (Jan-Dec) in sidebar

Technical Implementation
Tools Used
Microsoft Excel for dashboard creation
Pivot Tables for data aggregation
Charts & Graphs for data visualization
Conditional Formatting for visual indicators


Data Structure
Patient_Id | Admission_Date | Gender | Age | Race | Department | Admission_Flag | Satisfaction | Wait_Time


Key Calculated Fields
Admission rate percentage
Average wait times by department
Patient satisfaction trends
Monthly patient volumes


Usage Instructions
Filter Data: Use the month selector (Jan-Dec) to view specific periods
Compare Years: Toggle between 2023 and 2024 using year buttons
Department Analysis: Review referral patterns in the horizontal bar chart
Demographics: Analyze patient distribution by age groups and gender
Performance Metrics: Monitor satisfaction scores and wait times


Insights & Findings

Patient Demographics
Age Distribution: Fairly even across age groups (54-76 patients per group)
Gender Split: Slight female majority (53% vs 47%)
Race Distribution: Diverse patient population across multiple ethnicities

Operational Metrics
High Non-Referral Rate: 58% of patients require no specialist referral
General Practice: Most common referral (20% of patients)
Orthopedics: Second most common specialty referral

Performance Areas
Wait Time Optimization: 36-minute average suggests room for improvement
Patient Satisfaction: 4.96/10 score indicates significant improvement opportunities
Admission Efficiency: ~48% admission rate provides baseline for capacity planning

File Structure
hospital-er-analysis/
├── Hospital_Emergency_Room_Data.csv     # Raw patient data
├── ER_Dashboard.xlsx                    # Interactive Excel dashboard
├── README.md                           # Project documentation
└── analysis/
    ├── monthly_reports/                # Period-specific analyses
    └── visualizations/                 # Chart exports
    
Future Enhancements
Real-time Data Integration: Connect to live hospital systems
Predictive Analytics: Forecast patient volumes and wait times
Staff Scheduling: Correlate patient flow with staffing levels
Cost Analysis: Add financial metrics and resource utilization
Quality Metrics: Expand satisfaction surveys and outcome tracking

Data Privacy Note
All patient data has been anonymized with fictitious names and IDs while maintaining realistic demographic and operational patterns for analysis purposes.
