# Medical-Appointments No-Show Analysis.

### Project Overview
This project explores factors that influence patient no-shows for medical appointments in Brazil. The objective was to clean and analyze the data, extract meaningful insights, and present them through Power BI dashboard. 

### Data Sources
The data set used for this analysis is Medical Appointment No Shows: [Download here](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

### Tools Used
- Excel: Data cleaning, transformation, column creation.
- Power BI: Expolarotary data analysis, DAX, data modeling, visualization.

### Data cleaning in Excel
In the initial data preparation phase, I performed the following tasks:
- Converted ISO date fields to readable Excel dates.
- Extracted Appointment Day, Weekday, and calculated Appointment Delay.
- Converted binary fields(e.g., Scholarship, SMs_Received) to easier-readable label (Yes/No).

### Power BI Dashboard Highlights
- Calculated Key metrics including:
  - Total Appointments
  - Total No-Shows
  - No-Show Percentage
- Created WeekdaySort column to order weekday charts logically.
- Built interactive visuals to explore No-Show behavior.
- Added slicers to allow filtering by patient demographics and conditions.

### Key Insights
- Saturday had the highest no-show percentage of all weekdays.
- Older patients (60+) had the lowest no-show rates, while younger age groups missed appointments more.
- Patients who received SMS reminders were associated with an 11% higher no-show percentage rate.
- Scholarship recipients also had a higher no-show percentage rate.

### Recommendations
- Consider other forms of reminders or test new SMS content since the current SMS reminders were associated with higher no-show percntage.
- Focus on younger age-groups by creating tailored out reach to increase their show-up rate.
- Study socio-economic factors further since those with scholarships had a higher no-show rate which could indicate affordability issues in accessing medical facilities.

### Limitiations
- The data set does not give reasons for missing appointments which limits interpretation in no-show behavior.
