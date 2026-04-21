# HR-Analytics-Workforce-Insights-Capstone-Project

An end-to-end Python-based data analytics project designed to provide deep visibility into workforce dynamics, employee attrition, salary equity, and hiring trends. 

## 📝 Problem Statement
Understanding workforce dynamics and identifying flight risks are critical challenges for modern Human Resources departments. Without clear visibility into historical hiring trends, salary equity, and the root causes of attrition, businesses struggle to retain top talent, forecast headcount growth, and maintain operational stability. 

This project addresses these challenges by:
* Tracking and visualizing overall headcount and year-over-year (YoY) growth trends.
* Identifying key drivers and rates of employee attrition across different departments.
* Evaluating salary distributions and identifying gender-based pay disparities.
* Assessing employee tenure and hiring patterns to optimize future recruitment strategies.

## 💡 Solution & Key Features
This project provides a complete data-driven solution utilizing custom synthetic data generation, demographic profiling, and advanced Matplotlib/Seaborn visualization.

* **Synthetic Data Generation Pipeline:** Programmatically generates realistic HR records spanning 5 years, reflecting real-world complexities like gender pay gaps, salary noise, and tenure caps.
* **Workforce Demographics & Attrition Analysis:** Segments employees by department and tenure to identify organizational stability and primary flight risks (e.g., Better offers, Compensation, Personal reasons).
* **Compensation & Tenure Profiling:** Provides statistical breakdowns of average salaries and visualizes gender pay equity across various business units.
* **Interactive HR Analytics Dashboard:** A highly customized, cohesive multi-plot dashboard built using Matplotlib `GridSpec`.
* **Automated Textual Reporting:** Generates a clean, terminal-based textual summary report alongside the visual outputs.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 🚀 Key Results & Insights
* **Overall Attrition:** The company-wide attrition rate stands at **12.8%**, with Sales (**20.2%**) and Marketing (**15.6%**) experiencing the highest turnover.
* **Flight Risks:** The leading cause for employee departure is receiving a "Better offer," followed closely by "Compensation" and "Personal" reasons.
* **Growth Trends:** A Year-over-Year (YoY) headcount growth rate of **-12.2%** in 2024 indicates a workforce contraction or restructuring phase.
* **Tenure Concentration:** Over 70% of the active workforce has a tenure of 1 to 5 years, indicating a heavy reliance on mid-tenure employees.
* **Compensation:** The active median salary is **$83.0K**, with visualizations successfully highlighting minor gender wage variations across departments.

## 📂 Repository Structure
* `HR Analytics & Workforce Insights.ipynb`: The main Jupyter Notebook containing the end-to-end Python pipeline (data generation, KPI computation, visualization, and reporting).
* `hr_dashboard.png`: Exported comprehensive overview dashboard.
* `hr_hiring_deep.png`: Exported deep-dive visualization of hiring and growth trends.
* `hr_employee_data.csv`: The generated synthetic dataset exported for downstream use.

