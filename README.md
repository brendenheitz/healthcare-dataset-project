# Longitudinal Medical Registry & Financial Pipeline

## Project Overview
Engineered an end-to-end database pipeline using **SQLite** to process a 55,500-record longitudinal medical registry across a five-year operational timeline, culminating in an interactive **Power BI Desktop** dashboard tracking **$1.40 billion** in network billing.

## Key Features & Technical Highlights
* **Data Hygiene & Quality Enforcement:** Applied window partitioning logic (`ROW_NUMBER`), string cleaning rules (`TRIM`), and character casing transformations to ensure strict data integrity.
* **Anomaly & Error Remediation:** Eliminated 532 duplicate admission sequences and 108 records containing null financial values, successfully preserving a **99% data retention threshold**.
* **Feature Engineering:** Developed derived columns to segment length-of-stay calculations using Julian date differentials.
* **Business Intelligence:** Designed an interactive Power BI layout utilizing custom DAX formulas to analyze billing distribution across five major insurance providers.

## Tech Stack
* **Database:** SQLite
* **Data Transformation & Cleaning:** SQL (Window Functions, String Manipulation)
* **Visualization & BI:** Power BI Desktop (DAX)