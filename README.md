**💼 Employee Salary Prediction & Pay Gap Analysis
**

📌 Project Overview
This project predicts employee salaries using features such as job role, experience, education, and skills with Linear Regression.
Additionally, it investigates potential pay gaps (e.g., gender bias, role-based inequality).


This project demonstrates:
📊 Data Cleaning & Exploratory Data Analysis (EDA)
🤖 Machine Learning with Linear Regression
📈 Model Evaluation (R², RMSE)
💡 Business Insights for HR decision-making

📊 Dataset
File: employee_salaries.csv
Rows: 500 employees (synthetic dataset generated with realistic salary patterns)

Features:
employee_id → Unique identifier
job_role → Employee’s role (Data Scientist, Analyst, Engineer, Manager, HR)
experience_years → Years of work experience
education_level → Bachelors, Masters, PhD
gender → Male / Female
skills_score → Skill proficiency score (0–100)
salary → Target variable (annual salary in USD 💰)


🔎 Exploratory Data Analysis
📈 Salary increases strongly with experience years
🎓 Higher education → higher salaries
⚖️ Small gender pay gap observed (males earn slightly more)
👔 Managers & Data Scientists have highest average salaries


🤖 Model
Algorithm: Linear Regression
Train/Test Split: 80/20
Evaluation Metrics:
R² Score: ~0.82
RMSE: ~5000


📈 Results
Model successfully predicts salaries with high accuracy.
Identified key salary drivers: experience, education, skills.
Detected possible pay inequality across genders.


💡 Business Value
Helps HR teams create fair & data-driven compensation.
Detects salary gaps across roles, education levels, and genders.
Supports recruitment, retention, and budgeting decisions.
