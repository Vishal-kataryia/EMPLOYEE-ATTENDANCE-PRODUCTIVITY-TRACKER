# EMPLOYEE-ATTENDANCE-PRODUCTIVITY-TRACKER (Power BI)

An interactive Power BI report that turns 5,000 employee-day records (01 Jan to 07 Oct 2025, 250 employees) into a view of attendance, absenteeism, productivity and overtime. Built for the HCLTech Career Shaper Programme industry project.

## Key Findings
- Attendance is **84.3%**, 5.7 points below the 90% target.
- Absenteeism rate is **7.6%**; 143 of 682 absence days (21%) are unexcused.
- Finance (81.0%), Sales (82.0%) and Hybrid working (82.2%) have the lowest attendance.
- Average productivity score is **83.0**; overtime totals **2,303.5 hours**, and it barely lifts output (r = 0.18).

## Report Pages
1. Executive overview
2. Absenteeism analysis
3. Productivity and work patterns
4. Drivers and detail

## Data Model
Star schema: one Attendance fact table with Employee, Date and Threshold tables, plus a measure table of 61 DAX measures.

## How to Open
1. Install Power BI Desktop (Windows).
2. Download `EmployeeAttendance.pbix` from this repository.
3. Open it in Power BI Desktop. A PDF export of all four pages is also included for viewing without Power BI.

## Files
- `EmployeeAttendance.pbix`: the Power BI report
- `employee_attendance_productivity_dataset.csv`: source data
- `EmployeeAttendance_Dashboard.pdf`: export of the four report pages
- `Project_Report.docx`: full project report

## Notes
Educational project. The data is a sample of employee-days, so absence counts are not a full register. The report is for monitoring only, not for automated HR or disciplinary decisions.
## Snapshort link:

Author: Vishal, ABES Engineering College, Ghaziabad
