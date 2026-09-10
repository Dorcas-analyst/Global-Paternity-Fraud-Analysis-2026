# Global-Paternity-Fraud-Analysis-2026
An end-to-end data analytics and business intelligence project analyzing documented paternity fraud cases across countries and regions, with emphasis on legal protection, DNA-testing accessibility, financial severity, psychological impact, and discovery methods.

## My Role & Team
**Role:** Data Team Lead Analyst
**Team Structure:** 9 Data Analysts + 1 Project Manager
**Project Manager:** Matthew Dada
**Programme:** Vephla University — Simulations Capstone Programme, Team 1

As the Data Team Lead Analyst, I contributed to coordinating the team's analytical workflow and worked across data sourcing, data cleaning, feature engineering, dataset integration, analysis, documentation, and Power BI reporting.

## Project Objective
The objective was to transform fragmented secondary information from academic, institutional, demographic, and legal sources into a structured dataset and interactive dashboard capable of revealing patterns in:
* Legal protection
* DNA-testing accessibility
* Financial impact
* Psychological impact
* Economic consequences
* Discovery methods
* Legal challenge windows

## Tools & Technologies
* **Microsoft Excel**
* **Power Query**
* **Microsoft Power BI**
* **DAX**

## 📊 Dataset
The team consolidated four datasets into a Master Dataset containing:
* **1,284 records**
* **11 analytical variables**
The dataset included country, region, legal strength, legal protection, DNA access, discovery method, financial severity, psychological impact, economic consequences, and legal challenge-window variables.

## Data Analytics Workflow

```text
Secondary Data Sources
        ↓
Data Collection
        ↓
Data Cleaning & Standardization
        ↓
Feature Engineering
        ↓
Power Query Data Integration
        ↓
Master Dataset
        ↓
Power BI + DAX
        ↓
Dashboard & KPI Analysis
        ↓
Insights & Recommendations
```

## Data Preparation
Power Query was used to:
* Handle missing values.
* Remove 1,000+ duplicate records.
* Remove irrelevant blank rows.
* Standardize country names.
* Remove non-analytical columns.
* Create analytical categories.
* Merge four datasets using Left Outer Joins.

## Feature Engineering
The project created structured analytical variables from raw information, including:
* Legal Strength Score
* Legal Protection Level
* DNA Access Level
* Discovery Method Category
* Financial Severity
* Psychological Category
* Economic Category
* Challenge Window Category

## Power BI & DAX
DAX was used to create dynamic KPIs and analytical measures, including:
* Total Cases
* Average Legal Strength
* Percentage of High Financial Impact
* Percentage of Low DNA Access
* Strong Legal Cases
* Low DNA Access Cases

Text standardization using `TRIM()` and `UPPER()` was also applied within filtering logic.

## Key Findings
| Metric                     | Finding |
| -------------------------- | ------: |
| Total documented cases     |   1,284 |
| DNA Test discovery         |   55.5% |
| Medium legal protection    |   60.4% |
| High financial severity    |   83.8% |
| Trauma                     |   41.0% |
| Medium DNA accessibility   |   87.4% |
| Flexible challenge windows |   96.3% |
| Nigeria's share of records |   58.4% |
These findings indicate substantial legal, financial, psychological, and institutional dimensions within the available documented data.

## Recommendations
The analysis supported recommendations to:
* Strengthen legal frameworks surrounding paternity disputes.
* Improve access to affordable and regulated DNA testing.
* Expand psychological and family-support systems.
* Improve financial protection mechanisms.
* Strengthen data collection and reporting.
* Encourage multidisciplinary policy development.
* Improve international data standardization.

## Data Limitations
The project relied on secondary data, which introduced limitations including fragmented global reporting, inconsistent legal definitions, underreporting, missing information, regional representation bias, and uneven data availability.
Nigeria accounted for **58.4% of records**, so regional comparisons should be interpreted cautiously. The report also notes that the absence of Low DNA Access records may represent a data gap rather than evidence that low-access regions do not exist.

## Team Acknowledgement
This was a collaborative project involving **9 Data Analysts and 1 Project Manager**.
I served as the **Data Team Lead Analyst**. I acknowledge the contributions of the entire team:
**Project Manager:** Matthew Dada
**Data Analysts:** Akinleye Oyinkansola Mary, Oyibo Doras Oghenenyerhovwo, Modupe Okueso, Eniola Adelakun, Zainab, David Ojo, Adegbola Oluwakemi Esther, John Loveth Oluomachi, and Akpoveta Eguono Deborah.
Thank you to every team member who contributed to the research, data sourcing, preparation, analysis, documentation, visualization, coordination, and delivery of this project.

## Project Status

Completed as part of the **Vephla University Simulations Capstone Programme — Team 1**.
**Project Type:** Secondary Data Analysis / Business Intelligence
**Primary Tools:** Excel, Power Query, Power BI, DAX
**Role:** Data Team Lead Analyst
