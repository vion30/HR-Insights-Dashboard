# HR-Insights-Dashboard

# 📊 Power BI Dashboard - Employee & Payroll Analysis

## 🚀 Overview
This Power BI dashboard provides deep insights into employee distribution, payroll trends, and workforce performance. Using interactive visualizations, it enables HR and management to make data-driven decisions.

## 📌 Key Dashboards
### 1️⃣ Employee Summary Dashboard
🔹 **Purpose:** Analyze workforce distribution and hiring trends.

**Visuals:**
- 📈 **Employees Hired by Year** – Hiring trends from 2015 to 2018.
- 🏙️ **Employee Numbers by City** – Workforce distribution using a pie chart.
- 🏢 **Department-Wise Employee Count** – IT and Administration have the highest employees.

🖼️ **Dashboard Preview:** ![image](https://github.com/user-attachments/assets/6abd1dd6-5bea-4518-9566-5809aeea70a0)


---
### 2️⃣ Payroll Summary Dashboard
🔹 **Purpose:** Financial analysis of employee salaries and payroll distribution.

**Visuals:**
- 💰 **Actual Salary by Region & Group** – Distribution of salaries across regions.
- 📊 **Salary Paid Summary** – Total salary commitments.
- 📝 **Employee Salary Table** – Detailed salary breakdown.

🖼️ **Dashboard Preview:** ![image](https://github.com/user-attachments/assets/b20ee65e-5ddb-4e3c-ba8b-bdb3c1d7ffb5)


---
### 3️⃣ Active Employees Dashboard
🔹 **Purpose:** Analyze active employees across cities, regions, and departments.

**Visuals:**
- 📊 **Total Strength by Year (Waterfall Chart)** – Employee growth/decline.
- 🗺️ **Total Strength by City (Map)** – Workforce distribution geographically.
- 🎯 **Performance Score & Salary Table** – Employee performance vs. salary.

🖼️ **Dashboard Preview:** ![image](https://github.com/user-attachments/assets/d02fe1c3-60cf-4183-a29e-c633306ce387)


---
## 📂 Datasets Used
1. **Employee Data** (`Employee_Data.xlsx`)
   - Columns: `Employee Number`, `Full Name`, `Date of Birth`, `Hire Date`, `Salary`, `Bonus`, `Overtime`, `Department`, `Sick Days`, `Performance Score`, `Status`, `Resignation Date`, `Office Code`

2. **Salaries** (`Salaries.xlsx`)
   - Columns: `Salary Date`, `Employee Number`, `Actual Salary`, `Working Days`, `Paid Salary`, `Full Name`

3. **Offices** (`Offices.xlsx`)
   - Columns: `Office Code`, `City`, `Description`, `Region`, `Address`

---
## 🛠️ Power BI Features Used
✅ **Power Query Editor** – Data cleaning & transformation
✅ **DAX Functions** – `SUM()`, `CALCULATE()`, `IF()` for calculations
✅ **Visualizations** – Bar charts, pie charts, maps, tables
✅ **Data Relationships** – Employee data linked to salary & office datasets
✅ **Dynamic Filters** – Slicers for city, region, and department

---
## 🔍 Key Insights
- 🚀 **Hiring peaked in 2016 & 2017**, followed by a decline in 2018.
- 🏙️ **Pune, Hyderabad, and Mumbai have the highest workforce**.
- 🏢 **IT & Admin departments have the most employees**.
- 💰 **Salary distribution varies across regions**, with major hubs paying higher salaries.
- 📉 **Some low-performing employees have high salaries**, indicating potential salary restructuring needs.

---
## ❓ FAQs
### 📌 Q: What advanced DAX functions were used?
**A:** `CALCULATE` for conditional aggregations and `SUM` for salary totals.

### 📌 Q: How was data accuracy ensured?
**A:** Using Power Query transformations and validation checks.

### 📌 Q: How would you implement Row-Level Security (RLS)?
**A:** Creating roles with filters based on user permissions, e.g., department-based access.

---
## 📥 Installation & Usage
1. **Clone this repository:**
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. **Open Power BI Desktop**
3. **Load the provided datasets**
4. **Explore interactive dashboards**

---
## 🙌 Conclusion
This Power BI project showcases **data analysis, visualization, and reporting skills**. It delivers actionable insights into workforce and payroll trends, aiding strategic decision-making. 🚀📊

Feel free to explore and contribute! ✨


