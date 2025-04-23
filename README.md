Task 1 - Data Cleaning
📝 Task Overview
This task focused on preparing a messy dataset for analysis by performing essential data cleaning using Python and Pandas.

📊 Dataset Details
Name: Medical Appointment No Shows

Source File: KaggleV2-May-2016.csv

🧼 Cleaning Steps Performed
Renamed columns to follow snake_case (e.g., ScheduledDay ➡ scheduled_day)

Corrected typo: handcap ➡ handicap

Converted scheduled_day and appointment_day to proper datetime format

Standardized categorical values in gender and no_show columns (uppercase for consistency)

Converted patientid to integer for correct data type

Checked for duplicate rows → ✅ None found

Checked for missing values → ✅ None found

💾 Output
Cleaned dataset saved as:
📁Task 1 Cleaned Medical Appointment.csv

📚 Key Learnings
Hands-on experience cleaning real-world healthcare data using Pandas

Understood the importance of consistent formatting, correct data types, and clean column names before starting any analysis

