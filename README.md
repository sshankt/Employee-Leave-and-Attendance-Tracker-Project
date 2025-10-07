# 🧾 Employee Leave & Attendance Data Entry Project

📘 Project Overview

This project showcases my skills as a Data Entry Specialist.
I manually entered raw employee leave data from scratch into Excel, cleaned and formatted it, and created a professional dashboard using pivot tables and charts.
This project helped me understand how real-world data is handled — from typing to reporting.
![](https://github.com/sshankt/Employee-Leave-and-Attendance-Tracker-Project/blob/main/photo_6280350129860578581_w.jpg)
## 📂 Project Steps
###  1️⃣ Data Entry (Manual Typing)

Typed 80+ rows of employee leave and attendance data manually in Excel.

Columns included:
| Employee ID | Employee Name | Department | Designation | Leave Type | Leave Start Date | Leave End Date | Total Leave Days | Status | Remarks |

Ensured each row was entered carefully without copy-paste to simulate real data entry work.

### 2️⃣ Data Cleaning

Performed basic cleaning tasks to make the data accurate and consistent:

Used Spell Check (F7) to correct typing errors.

Applied TRIM() formula to remove extra spaces.

Checked for missing values in important columns.

Used Remove Duplicates option to clean repeated rows.

Standardized text values (e.g., Approved / Pending / Rejected).

### 3️⃣ Data Formatting

Formatted the data to make it more readable and professional:

Bold and center-aligned headers.

Applied consistent date format (dd-mm-yyyy).

Used number format for Total Leave Days.

Applied borders and alternate row colors for better visibility.

Froze header row for easier navigation.

### 4️⃣ New Columns Created

Added extra columns to make the dataset analysis-ready:

Total Leave Days → =DATEDIF(Leave Start Date, Leave End Date, "D")+1

Month → =TEXT(Leave Start Date, "mmmm")

Year → =YEAR(Leave Start Date)

### 5️⃣ Conditional Formatting

Used color-based formatting to make important patterns stand out:

Status column:

Approved → Green

Pending → Yellow

Rejected → Red

Total Leave Days greater than 3 → Highlighted in Light Blue

### 6️⃣ Data Sorting & Filtering

Converted data to a Table using Ctrl + T.

Sorted and filtered data by Department, Status, and Leave Type for quick insights.

### 7️⃣ Dashboard & Pivot Tables

Created Pivot Tables to summarize and analyze the data:

Leaves by Department

Rows: Department

Values: Sum of Total Leave Days

Leaves by Status

Rows: Status

Values: Count of Employee ID

Top Employees by Total Leave Days

Rows: Employee Name

Values: Sum of Total Leave Days

Charts Used:

Bar Chart → Total Leaves by Department

Pie Chart → Leave Status Distribution

Column Chart → Top Employees by Leave Days

### 8️⃣ Insights

From the dashboard analysis:

HR department had the highest number of approved leaves.

Sales team showed more pending leave requests.

Most employees took Casual Leave for 2–3 days.

Rajesh Kumar had the longest leave duration.

### 9️⃣ Tools Used

Microsoft Excel for typing, cleaning, and visualization

Functions: DATEDIF, TEXT, YEAR, TRIM

Features: Conditional Formatting, Pivot Tables, Charts

### 🧠 Skills Demonstrated

Manual Data Entry

Data Cleaning & Formatting

Excel Formulas & Functions

Conditional Formatting

Pivot Table & Dashboard Creation

Reporting & Analysis

### 📊 Final Output

The final Excel file includes:

Raw Data Sheet – Manually entered data

Cleaned Data Sheet – Formatted and verified data

Pivot Table & Charts Sheet – Dashboard with insights

### 🏁 Conclusion

This project demonstrates my ability to handle real-world data like a professional Data Entry Specialist — from typing and cleaning to reporting and analysis. It helped me improve my Excel efficiency, attention to detail, and understanding of business reporting.
