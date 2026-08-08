# HR Attrition Analytics using Microsoft Fabric & Power BI

An end-to-end HR analytics solution built using Microsoft Fabric and Power BI to identify employee attrition trends and enable interactive workforce analysis.

---

## Project Overview

This project demonstrates a complete Microsoft Fabric analytics workflow—from data ingestion to report deployment.

The solution imports HR employee data from GitHub using Dataflow Gen2, performs data transformation with Power Query, stores the data in a Lakehouse (Delta Tables), creates a Semantic Model, and builds interactive Power BI reports that are published to Microsoft Fabric.

---

## Business Problem

HR teams need to understand:

- Which departments have the highest attrition?
- Which salary bands experience more employee turnover?
- Does age, gender, education or business travel influence attrition?
- Which job roles require immediate retention efforts?

This dashboard provides interactive insights to support workforce planning and retention strategies.

---

## Architecture

```
GitHub CSV
      │
      ▼
Dataflow Gen2
      │
      ▼
Lakehouse (Delta Tables)
      │
      ▼
Semantic Model (DirectLake)
      │
      ▼
Power BI Desktop
      │
      ▼
Power BI Service
      │
      ▼
Dashboard • App • Scheduled Refresh
```

---

## Microsoft Fabric Components Used

- Dataflow Gen2
- Power Query
- OneLake
- Lakehouse
- Delta Tables
- Semantic Model
- DirectLake
- Power BI Desktop
- Power BI Service
- Dashboard
- Power BI App
- Scheduled Refresh
- Column Level Security (CLS)

---

## Data Transformation

Performed in Dataflow Gen2 using Power Query.

- Data type corrections
- Data cleaning
- Salary Band custom column
- Age Group custom column
- Business Travel Display custom column
- Loaded transformed data into Lakehouse

---

## Reports

### Overview Report

Provides high-level KPIs including:

- Attrition Rate
- Employees Left
- Total Headcount
- Average Monthly Income
- Average Tenure
- Department Analysis
- Salary Band Analysis
- Job Role Analysis
- Decomposition Tree

---

### Deep Dive Report

Provides detailed analysis by:

- Age Group
- Gender
- Education
- Marital Status
- Business Travel
- Overtime

---

## Security

Implemented:

- Column Level Security (CLS) for Monthly Income

---

## Deliverables

- Interactive Power BI Report
- Microsoft Fabric Dashboard
- Power BI App
- Scheduled Refresh
- End-to-End Microsoft Fabric Pipeline

---

## Repository Structure

```
Dataset/
Reports/
Screenshots/
README.md
```

---

## Skills Demonstrated

- Microsoft Fabric
- Dataflow Gen2
- Power Query (M)
- Lakehouse
- OneLake
- Delta Tables
- Semantic Model
- DirectLake
- Power BI
- DAX
- Column Level Security (CLS)
- Dashboard Design
- Business Intelligence
