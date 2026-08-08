HR Attrition Analytics using Microsoft Fabric & Power BI


📌 Project Overview

Developed an end-to-end HR Analytics solution using Microsoft Fabric and Power BI to analyze employee attrition patterns. The solution automates data ingestion, transformation, modeling, reporting, security, and deployment to help HR teams identify key factors influencing employee turnover.

🎯 Business Requirements

The dashboard answers the following business questions:

What is the overall employee attrition rate?
Which departments experience the highest attrition?
Does salary influence employee attrition?
Which age groups are leaving the organization?
Does overtime contribute to employee turnover?
How do education, marital status, gender, and business travel affect attrition?


🏗️ Solution Architecture

<img width="278" height="312" alt="image" src="https://github.com/user-attachments/assets/a49cc77a-5d55-45b9-85c1-d2b03b2cc78b" />






🔄 Microsoft Fabric Workflow

GitHub CSV

↓

Dataflow Gen2

↓

Power Query Transformations

↓

Lakehouse (Delta Tables)

↓

DirectLake Semantic Model

↓

Power BI Desktop Reports

↓

Power BI Service

↓

Dashboard

↓

Power BI App

↓

Scheduled Refresh + Column Level Security

⚙️ Tech Stack
Microsoft Fabric
Dataflow Gen2
Power Query (M)
Lakehouse
Delta Tables
DirectLake Semantic Model
Power BI Desktop
Power BI Service
DAX
Dashboard
Power BI App
Column Level Security (CLS)
Scheduled Refresh
GitHub

📊 Dashboard Preview
Overview

<img width="475" height="337" alt="image" src="https://github.com/user-attachments/assets/6d2c63b3-dedb-4340-a438-90ea8157f8c4" />


Deep Dive

<img width="476" height="338" alt="image" src="https://github.com/user-attachments/assets/124c1c2d-3146-4a39-be56-3ff22f3ce13c" />

Dashboard

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/eed4a4e3-3a65-41e0-8be8-e5b0f9ddeac9" />


Power BI App

<img width="959" height="379" alt="image" src="https://github.com/user-attachments/assets/dab0bc6c-25fa-4cac-9b58-4263cc731007" />


📈 Key Insights
Overall Attrition Rate: 16.1%
Sales department recorded the highest attrition.
Employees earning below 3K experienced the highest turnover.
Overtime employees showed significantly higher attrition.
Younger employees had comparatively higher attrition rates.
🔒 Security & Governance
Implemented Column Level Security (CLS) for sensitive Monthly Income data.
Published reports through a Power BI App.
Configured Scheduled Refresh.
Used DirectLake Semantic Model for high-performance reporting.
🛠 Skills Demonstrated
Microsoft Fabric
OneLake
Dataflow Gen2
Power Query
Lakehouse
Delta Tables
DirectLake
Semantic Modeling
DAX
Power BI
Dashboard Design
Power BI Service
Column Level Security
Scheduled Refresh
GitHub
