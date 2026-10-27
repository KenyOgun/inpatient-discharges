# 🏥 Healthcare Data Analysis & Executive Reporting (LIHN)

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-EDA_|_Financial_|_Operations-blue?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Healthcare_Analytics-red?style=for-the-badge)

## 📌 Executive Summary

This project delivers an end-to-end data analysis of over **339,000 inpatient discharges** (2015 SPARCS dataset) for the fictional **Long Island Healthcare Network (LIHN)**. Operating as a Senior Data Analyst in LIHN's Business Intelligence Unit, I developed four executive-grade diagnostic and descriptive reports using **Microsoft Excel**.

The goal of this analysis is to inform executive decision-making across **Demographic Profiling**, **Financial Optimization**, **Reimbursement Strategy**, and **Operational Efficiency & Quality of Care**.

---

## 🎯 Analytical Framework: Prepare, Analyze, Consider

The project follows a structured 3-step analytics methodology:

1. **Prepare:** Extracted and cleaned raw CSV data (~125MB+, ~339k records), resolved data quality issues, created custom length-of-stay (LOS) 30-day binning, and parsed string outliers (e.g., converting `120+` text values for mathematical modeling).
2. **Analyze:** Conducted Exploratory Data Analysis (EDA), tested domain hypotheses, executed Pareto analyses (80/20 rule), and performed multi-variable aggregations.
3. **Consider:** Designed executive-ready dashboards and print-optimized tabular reports tailored for C-suite decision-makers (CEO, CFO, COO, Director of Quality Assurance).

---

## 🛠 Key Project Tasks & Findings

### 📑 Task 1: Descriptive Report of Patient Discharges

- **Objective:** Establish baseline demographic profiles, admission types, diagnosis distributions, and discharge dispositions.
- **Key Insights:**
  - Patients aged **70+** represented the largest share of total discharges (**34.5%**), while the **50–69** age bracket accounted for **26.9%**.
  - Diseases of the **Circulatory System (15.4%)** and **Digestive System (9.7%)** were the leading causes of inpatient admission.
  - Assessed Risk of Mortality (APR) distributions against age groups, confirming expected clinical risk patterns.

### 💰 Task 2: Financial Analysis & Revenue Optimization

- **Objective:** Analyze gross margin, total billed charges vs. incurred costs, cost variance by facility, and length of stay (LOS) financial impact.
- **Key Insights:**
  - **Pareto Analysis (80/20 Rule):** Demonstrated that **20.9% of procedure types (48 out of 230)** accounted for **80% of total network revenue** ($19.17B gross charges).
  - **Cost Variance:** Identified **Nassau University Medical Center** as having the highest average discharge cost ($23,044 vs. network average of $15,557, an +81% variance), driven by complex case-mix triage.
  - **Sensitivity Analysis:** Modeled a 10% cost inflation scenario for 2016 to flag at-risk facilities and low-margin procedure codes.

### 💳 Task 3: Payment Typology & Reimbursement Strategy

- **Objective:** Evaluate payer mix (Medicare, Medicaid, Private Insurance, BCBS, Self-Pay), compute net margins, and support payer contract negotiations.
- **Key Insights:**
  - Network-wide Gross Margin averaged **72%** ($13.9B Gross Profit on $19.2B Charges).
  - **Low-Margin Typologies:** Identified _Miscellaneous/Other_ (58%) and _Self-Pay_ (59%) as key margin risks requiring targeted cross-subsidization strategies.
  - Evaluated private health insurance procedure margins against Blue Cross/Blue Shield (BCBS) baseline rates to establish negotiation floors for expiring contracts.

### 🏥 Task 4: Operational Efficiency & Quality of Care

- **Objective:** Examine throughput (LOS vs. Admission Type), Emergency Department (ED) utilization, and Severity of Illness vs. Patient Outcomes (_Expired_, _Home Care_, _Left Against Medical Advice_).
- **Key Insights:**
  - Mapped average LOS across facilities using dual-axis combo visualizers to spot operational throughput bottlenecks in Elective admissions.
  - Evaluated Emergency Department utilization for _Minor_ and _Moderate_ severity cases to pinpoint facilities over-relying on ED resources for low-acuity admissions.

---

## 🧰 Technical Skills & Tools Used

- **Microsoft Excel Capabilities:**
  - Advanced Lookups & Logic (`XLOOKUP`, `VLOOKUP`, `NESTED IF`, `AND/OR`)
  - Statistical Functions (`AVERAGE`, `MEDIAN`, `RANGE`, Distribution Percentiles)
  - Data Modeling & Cleaning (Text-to-Columns, Custom Binnings, Handling `#DIV/0!`, Data Type Conversion)
  - Dynamic PivotTables & PivotCharts
  - Custom Dashboard Design (Print Layout Optimization, Conditional Formatting, Dual-Axis Combo Charts)
- **Analytical Techniques:**
  - Pareto Analysis (80/20 Rule)
  - Financial Modeling (Gross Margin %, Cost-to-Charge Ratios, Inflation Sensitivity Modeling)
  - Operational Risk Profile & Clinical Outcome Cross-Tabulation

---

## 📁 Repository Structure

```text
.
├── data/
│   └── raw_data_notice.md         # Instructions to download NY SPARCS 2015 Dataset
├── reports/
│   ├── Task1_Descriptive_Report.pdf
│   ├── Task2_Financial_Analysis.pdf
│   ├── Task3_Payment_Typology.pdf
│   └── Task4_Operational_Efficiency.pdf
├── LIHN_Healthcare_Analysis.xlsx   # Main Excel Workbook containing analysis & dashboards
└── README.md                       # Project Documentation
```

---

## 🌐 Dataset Source

- **Dataset:** New York State Department of Health - _Hospital Inpatient Discharges (SPARCS De-Identified)_
- **Service Area Filter:** Long Island Region (2015)
- **Records Analyzed:** ~339,277 Discharges
- **Source:** [health.data.ny.gov](https://health.data.ny.gov/)

---

## 💼 Bullet Points for Resume / Portfolio

You can adapt the following bullet points for your resume:

- **Healthcare Data Analysis & Financial Modeling:** Analyzed 339,000+ NY State SPARCS inpatient discharge records using Microsoft Excel to evaluate network profitability, operational throughput, and demographic risk profiles.
- **Pareto & Margin Optimization:** Conducted a Pareto (80/20) analysis on $19.2B in gross billed charges, discovering that 20.9% of procedure types generated 80% of revenue, and identified key low-margin payer typologies to aid executive contract renegotiations.
- **Operational Reporting & Executive Dashboards:** Designed four executive-level dashboards evaluating Average Length of Stay (ALOS), Emergency Department utilization, and mortality outcomes relative to illness severity across 23 regional healthcare facilities.
