# HR_Analysis_Dashboard_Full_Insight
This analysis project presents an interactive Power BI dashboard analyzing HR Analytics data and HR employee data. It visualizes trends in service years, Job levels, departments, Business travels, Education_Field, Gender, Job_Roles, Retreanchment_Status, Job Ratings, and Promotion Status

---

## 📃Project Overview
This project presents a comprehensive HR Analytics Dashboard designed to help stakeholders understand workforce trends, identify high-risk employee segments, monitor promotion readiness, and assess factors influencing retention and productivity.

The dashboard consolidates multiple HR metrics into an intuitive interface with three main navigation sections:
- **Home** – Overall workforce overview
- **Detail** – Departmental and job-level insights
- **Action** – Attrition analysis, risk identification, and employee-level decisions
The solution allows management to proactively address HR challenges, optimize workforce planning, and improve employee satisfaction.

The dashboard helps answer critical HR Analytics and employee data questionds:
- How many total employees are available in the HR dataset
- How many numebers of employees are **Due for promotion** and also **Not Due for promotion**
- What are the total numbers of **Active workers** and those that are retreached
- What are the number of employees across different Job Levels
- The total number of employees coming from **Very far distance, Very close distance and Close distance**
- Percentage Ratings across all employees

  ---
## Data Source
![Download Here](HR_Analytics_Data.csv)

  ---

## 📈 Key Metrics (Overall)
| Metric | Values |
|--------|---------|
|**Total Employees**| 1,470 |
|**Male** |882 (60%)|
|**Female**| 588 (40%)|
|**Active Workers**| 1,353 (92%)|
|**Retrenched/At-Risk**| 117 (8%)|
|**Not Due for Promotion**| 1,398 (95.1%)|
|**Due for Promotion**| 72 (4.9%)|

 ---

## 🛠Tools Used
- Power BI – Dashboard creation, DAX calculations, visualization
- Excel / CSV – Original dataset and preprocessing
- Power Query – Data cleaning and transformation
- DAX – KPIs, measures, and calculated columns
- GitHub – Version control and documentation

 ---
 
## 🧹Data Preparation Steps
- Loaded the dataset into Power BI from Excel/CSV.
- Cleaned the data in Power Query by removing duplicates and handling null values.
- Standardized categorical fields such as JobRole, Department, and EducationField.
- Converted data types including dates, integers, and text fields.
- Normalized key columns such as DistanceFromHome, YearsAtCompany, and Salary.
- Performed feature engineering in DAX, creating flags for Due for Promotion, Will be Retrenched, and Attrition.
- Generated additional metrics including gender ratios, job satisfaction groups, and service year categories.
- Established relationships between employee dimension tables and fact tables to support accurate aggregation.
- Structured the dashboard using navigation buttons (Home, Detail, Action) and bookmarks for seamless page switching.

 ---
 
## 📈 Dashboard Insights
HR_Analysis_Dashboard_Full_Insight

____________________________________________________________

### Employee Demographics & Structure
- Workforce is male-dominant (60%), indicating a gender imbalance.
- Majority of employees live far from the office (64%), which may contribute to attrition or lateness.

### Promotion & Career Growth
- Only 4.9% are due for promotion, implying either:
  - strict promotion criteria, or
  - a relatively junior workforce.
- Research & Development has the highest number of promotion-ready employees.

### Retrenchment & Attrition Risk
- 117 employees identified as high risk for retrenchment.
- Attrition data shows:
  - Yes: ~16%
  - No: ~84%
- Majority of at-risk employees belong to Sales and Technical roles.

## Job Satisfaction & Overtime
- High overtime correlates with higher attrition risk.
- Low job satisfaction is prevalent (569 employees), signaling potential HR intervention needs.

### Department-Level Insights
- R&D and Sales departments have large numbers of employees both due for promotion and at risk of retrenchment, indicating performance or workload pressure.
- Job roles like Laboratory Technicians, Sales Executives, and Research Scientists have the largest workforce distribution.

### Marital Status & Travel Impact
- Married employees (673) constitute the largest workforce segment.
- Frequent travel roles show signs of burnout and higher attrition likelihood.

