# Global Data Job Market Analysis

---

### 📌 Project Overview
This project analyzes global data-related job postings to uncover:
- In-demand skills across roles
- Skill specialization patterns
- How job requirements differ between Data Analysts, Data Scientists, and ML Engineers

The goal is to translate raw job-market data into actionable career insights.

---

### 📂 Datasets Used
1. **job_postings.csv** – Job titles, companies, locations, and roles
2. **job_skills.csv** – Skills required per job posting (multi-skill rows cleaned and exploded)
3. **data_science_job_salaries.csv** – Salary information by role, experience, and location

---

### 🧹 Data Cleaning
- Removed duplicate salary records
- Normalized job titles into three core roles
- Split multi-skill rows into individual skills
- Standardized skill naming

---

### 🔍 Exploratory Data Analysis (EDA)
- Skill frequency analysis
- Role-wise skill distribution
- Heatmaps for skill-role relationships
- Bar charts for top skills

---

## 💰 Salary Insights

- Median salary analysis indicates that **ML Engineers** are the highest-paid among data roles, followed by **Data Scientists**, with **Data Analysts** earning comparatively less.
- Salary distributions widen significantly with experience level, suggesting that **seniority has a stronger impact on compensation than job title alone**.
- Senior and executive roles show greater salary variance, reflecting differences in company size, location, and responsibilities.

These findings provide context for skill demand analysis by highlighting how compensation evolves across roles and experience levels.
---

### 📊 Key Insights
- Data Analysts focus on SQL, Excel, and BI tools
- Data Scientists emphasize Python, ML, and statistics
- ML Engineers are dominated by deployment, frameworks, and deep learning tools

---

### ⚠️ Limitations
- Job postings do not guarantee actual on-the-job usage
- Salary data is regionally skewed
- Skill frequency ≠ skill mastery

---

### 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Jupyter Notebook

---

### 📌 Conclusion
This project demonstrates real-world data cleaning, analysis, and storytelling skills applicable to entry-level data roles.

---
