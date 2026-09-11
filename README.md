# HR-Analytics-Dashboard

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-blue?style=for-the-badge)]()
[![Excel](https://img.shields.io/badge/Data_Source-Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)]()

---

## 📌 Executive Summary
An interactive Power BI dashboard designed to monitor workforce distribution, compensation structure, departmental headcount, and bonus incentives across organizational divisions.

🔗 **[Live Interactive Report Link]**(https://your-powerbi-public-link-here) *(optional)*

---

## 🖥️ Dashboard Preview
---

## 💡 Key Business Questions Answered
* **Headcount by Department:** Which business units maintain the highest concentration of human capital?
* **Payroll & Bonus Disparity:** How does compensation distribute across office locations and departments?
* **Tenure & Hiring Trends:** Evaluating hiring influx based on Date of Joining (DOJ).

---

## 🛠️ Tech Stack & Methods
* **Data Modeling:** Star Schema linking Employee dimension to Department lookup tables.
* **Power Query:** Cleansed missing bonus values, normalized city names, and formatted date hierarchies.
* **DAX Formulas:** Custom calculations for average salary, bonus-to-salary ratios, and dynamic KPI cards.

```dax
// Example: Total Compensation Measure
Total Compensation = 
SUM(Emp[Salary]) + SUM(Emp[Bonus])
```

---

## 🚀 How to View & Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/hr-analytics-dashboard.git
   ```
2. Open `HR_Analytics_Dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. If data source paths prompt an update, point the source to `data/4. HR Database.xlsx`.

