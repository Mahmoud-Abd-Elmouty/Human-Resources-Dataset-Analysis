# 👥 Human Resources Dataset Analysis

### Power BI • Power Query • DAX

---

# 📌 Project Name

**Human Resources Dataset Analysis**

---

# 💡 Project Idea

This project analyzes Human Resources (HR) data using **Power BI** to uncover insights that support better workforce decisions. It is part of the **Digital Egypt Pioneers Initiative (DEPI)** data analysis track.

The project focuses on analyzing:

- Employee satisfaction levels
- Employee attrition and retention
- Workforce demographics and trends
- Factors affecting employee performance and turnover

The project also includes data cleaning and preprocessing, DAX measures, and an interactive dashboard that answers key business questions for HR decision makers.

---

# 🎯 Project Objective

- Clean and prepare employee data for analysis
- Define the key analytical questions that matter to HR decision makers
- Answer these questions through an interactive Power BI dashboard
- Provide insights and recommendations to support data-driven decisions

### Example Analysis Questions
- What is the relationship between employee age and satisfaction level?
- Which departments and job roles have the highest attrition?
- Do salary or years of experience affect satisfaction and retention?

> ✅ The analysis questions were defined after reviewing the dataset.

---

# 📂 Project Resources

| Resource | Link |
| -------- | ---- |
| Project Files (Google Drive) | [To be added] |
| Dataset Source | [Google Drive - Data Folder](https://drive.google.com/drive/folders/1iKGkAH_9yPngDTW43Y2QekH7GvbMGHwh?usp=sharing) |

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
| ---- | ------- |
| Power BI | Data cleaning, analysis, and dashboard development |
| Power Query | Data cleaning and transformation (ETL) |
| DAX | KPIs and calculated measures |
| PowerPoint | Final presentation and storytelling |

---

# 🗓️ Work Plan

### Project Workflow

```mermaid
graph TD
A[📥 Data Collection] --> B[🔍 Data Understanding]
B --> C[🧹 Data Cleaning & Preprocessing]
C --> D[❓ Defining Analysis Questions]
D --> E[📐 Data Modeling & DAX Measures]
E --> F[📊 Dashboard Development]
F --> G[📖 Final Report & Presentation]
style A fill:#c8e6c9,stroke:#2e7d32,color:#1b5e20
style B fill:#c8e6c9,stroke:#2e7d32,color:#1b5e20
style C fill:#c8e6c9,stroke:#2e7d32,color:#1b5e20
style D fill:#c8e6c9,stroke:#2e7d32,color:#1b5e20

### Project Timeline

| Phase | Duration | Status |
| ----- | -------- | ------ |
| 🧹 Data Cleaning & Preprocessing | Week 1 | ✅ Done |
| ❓ Analysis Questions | Week 2 | ✅ Done |
| 📊 Dashboard Development | Week 3 | ⬜ Not started |
| 📖 Final Report & Presentation | Week 4 | ⬜ Not started |

---

# 👥 Team Members

| Name | Role |
| ---- | ---- |
| Mahmoud Abdel Moaty | Dashboard & DAX Lead |
| Khalid Khalifa | Data Cleaning & Preprocessing |
| Mohamed Rageh | Attrition Analysis & Final Report |

---

# 🧩 Roles & Responsibilities

| Name | Responsibilities |
| ---- | ---------------- |
| Mahmoud Abdel Moaty | Build the Power BI data model, write the DAX measures, design the dashboard pages, coordinate the team, and analyze employee age and satisfaction level. |
| Khalid Khalifa | Clean and transform the dataset in Power Query (missing values, duplicates, data types), and maintain the Data Dictionary. |
| Mohamed Rageh | Analyze attrition by department and job role, study the effect of salary and years of experience on retention, then write the final report and prepare the PowerPoint presentation. |

---

# 🧹 Data Cleaning & Preprocessing

> ✅ Completed in Week 1.

### Dataset Overview
- **Employee.csv:** 1,470 employees, 23 columns, no duplicate IDs and no missing values
- **PerformanceRating.csv:** 6,709 review records covering 1,280 employees, no missing values
- **Lookup tables:** EducationLevel, RatingLevel, and SatisfiedLevel (used to map the numeric codes)

### Challenges Found
- Some text values contain trailing spaces (e.g. "Marketing ", "Satisfied ", "High School "), which affect grouping and filtering
- Some employees have multiple performance reviews, so satisfaction must be handled at the right level before averaging

### Cleaning Steps
> ⏳ To be listed: the final cleaning steps applied (trimming text, data types, date formats, and relationships in the data model).

---

# 📄 Dashboard Pages

| Page | Description |
| ---- | ----------- |
| [To be added] | [To be added] |

---

# 📈 KPIs

| KPI | Definition | Current Value |
| --- | ---------- | ------------- |
| Total Headcount | Number of employees | 1,470 |
| Attrition Rate | Employees who left ÷ total employees | 16.12% |
| Average Age | Mean employee age | 29.0 years |
| Average Salary | Mean employee salary |
