# HR-Analytics-Dashobard
# HR Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

An interactive, end-to-end **Power BI Dashboard** focused on Human Resources workforce analytics. This project transforms raw organizational employee logs into actionable insights, enabling executives and HR managers to monitor workforce distribution, optimize retention strategies, and dissect overall attrition dynamics.

---

## 📌 Table of Contents
- [Executive Summary](#-executive-summary)
- [Key Features \& Insights](#-key-features--insights)
- [Tech Stack Used](#-tech-stack-used)
- [System Architecture](#-system-architecture)
- [Workbook & Model Structure](#-workbook--model-structure)
- [Key Metrics Tracked (DAX Measures)](#-key-metrics-tracked-dax-measures)
- [How to Access the Dashboard](#-how-to-access-the-dashboard)
- [Future Improvements](#-future-improvements)

---

## 📊 Executive Summary
Understanding structural demographics and employee attrition is critical to minimizing organizational turnover costs. This dashboard solves complex reporting tasks by contextualizing employee lifecycle metrics into uniform visual reports. It isolates high-risk turnover metrics, traces departmental structural anomalies, and identifies career performance benchmarks to drive data-backed HR interventions.

---

## 💡 Key Features & Insights
- **Active Workforce Aggregations:** Instantly view real-time calculations of headcount distributed across specific geographic locations, job levels, and organizational divisions.
- **Attrition Dissection Deep-Dive:** Isolate high-turnover variables by analyzing specific risk factors including low tenure rates, low job satisfaction scores, long commute distance metrics, or standard salary discrepancies.
- **Demographics Distribution Mapping:** Comprehensive visual mapping of gender structures, age groups, standard job role distributions, and education tiers.
- **Performance vs. Loyalty Evaluation:** Cross-evaluate performance appraisals against organizational tenure benchmarks to identify if top performers are leaving prematurely.

---

## 🛠 Tech Stack Used
* **Power BI Desktop:** Core platform used for data modeling, analytical engineering, and data visual engineering.
* **Power Query Editor:** Utilized for data ingest cleaning pipelines, conditional columns generation, standard typecasting, and semantic profiling.
* **DAX (Data Analysis Expressions):** Engineered explicitly for writing robust semantic model measures and custom filter evaluation contexts.
COUNT(FactEmployee[EmployeeID]), FactEmployee[Attrition] = "No")
