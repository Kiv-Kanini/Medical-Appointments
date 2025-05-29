# Medical-Appointments No-Show Analysis.

### Project Overview
This project explores factors that influence patient no-shows for medical appointments in Brazil. The objective was to clean and analyze the data, extract meaningful insights, and present them through Power BI dashboard. 

### Data Sources
The primary data set used for this analysis is xxxxx containing details

### Tools Used
- Excel: Data cleaning, transformation, column creation
- Power BI: Expolarotary data analysis, DAX, data modeling, visualization

### Data cleaning in Excel
In the initial data preparation phase, we performed the following tasks:
- Converted ISO date fields to readable Excel dates
- Extracted Appointment_Dy, Weekday, and calculated Appointment Delay
- Converted binary fields(e.g., Scholarship, SMs_Received) to human-readable label (Yes/No)

### Power BI Dashboard Highlights
- Calculated Key metrics including:
  - Total Appointments
  - Total No-Shows
  - No-Show Percentage

- Created WeekdaySort column to order weekday charts logically
- Built interactive visuals to explore No-Show behavior
- Added slicers to allow filtering by patient demographics and conditions

### Key Insights
- Saturday had the highest no-show percentage of all weekdays.
- Older patients(60+) had the lowest no-show rates, while younger age groups missed appointments more
- Patients who received SMS reminders were associated with an 11% higher no_show percentage rate
- Scholarship recipients also had a higher no-show percentage rate 
