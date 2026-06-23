# Data Analytics Portfolio

Welcome to my data analytics portfolio. This repository showcases end-to-end business intelligence solutions built to optimize operational efficiency, track regulatory compliance, and deliver actionable clinical insights in the healthcare sector.

---

## 1. Care Management Transition of Care (TOC) & Readmissions Dashboard

### Project Overview
This dashboard tracks the effectiveness of Care Management interventions during patient transitions of care, monitoring both the operational success of outreach efforts and performing deep-dive clinical analytics on 30-day hospital readmission rates. 

### Key Features
* **TOC Outreach & Engagement:** A combo chart tracks TOC event volume against the percentage of cases contacted within business-day goals, alongside "successful contact" engagement rates.
* **30-Day Readmission Analytics:** Measures the volume and percentage of TOC cases resulting in an inpatient readmission within 30 days. Includes interactive Line of Business (LOB) filtering for DSNP and Medicare.
* **Geographic & Root-Cause Tracking:** Tracks a 6-month history of readmission rates by state (with a conditional formatting threshold set at `< 8%`), alongside root-cause analysis identifying the top 5 readmitting servicing providers and primary diagnosis codes.
* **Data Freshness Transparency:** Features a "Readmit Max Date" KPI card to clearly communicate claims-lag data thresholds to stakeholders.

### Gallery
> *Replace the image filename below with the screenshot that matches this dashboard (e.g., assets/images/IMG_1521.jpeg)*
![TOC and Readmissions Dashboard](assets/images/IMG_1521.jpeg)

---

## 2. Behavioral Health Operations & Population Health Dashboard

### Project Overview
An end-to-end Power BI solution providing a comprehensive view of Behavioral Health (BH) departmental performance, ranging from clinical screening timeliness to call center operational metrics.

### Key Features
* **Screening & Outreach Timeliness:** Tracks total BH screening cases and measures the percentage of successful "timely" outreach to ensure compliance with strict contact windows.
* **Case Lifecycle & Trends:** Utilizes regional donut charts to visualize average "days open" per case by CCO region, alongside monthly bar charts monitoring evaluation volume fluctuations.
* **Population Health & SDOH:** Features longitudinal analysis of Social Determinants of Health (SDOH) by CCO region and a 15-month look-back on priority populations with interactive sliders to isolate Severe and Persistent Mental Illness (SPMI) percentages.
* **Call Center Scorecard & SLA Compliance:** Monitors inbound call volumes, speed-to-answer metrics (under/over 30 seconds), abandonment rates, and normalized volumes per 1,000 members. Uses conditional formatting to flag metrics falling below service levels.

### Gallery
> *Replace the image filename below with the screenshot that matches this dashboard*
![Behavioral Health Dashboard](assets/images/IMG_1526.jpeg)

---

## 3. Care Management Call Center Analytics (Dashboard Enhancement)

### Project Overview
A dynamic, time-phased dashboard enhancement integrated into an existing enterprise reporting system to provide leadership with short-term historical trends for rapid staffing and regional resource shifts.

### Key Features
* **Dynamic Time Intelligence:** Implemented user-controlled parameters allowing seamless toggling between Weekly and Monthly data aggregations.
* **Rolling 4-Week Lookback:** Features specialized sidebar graphs displaying call volumes and critical operational KPIs (Call Service Level and Abandoned Rate) across a rolling 4-week window (Current Week, 1, 2, 3, and 4 weeks ago) broken down by CCO Region.
* **Seamless Architecture Integration:** Developed within the framework of an existing organizational data model, expanding capabilities without disrupting legacy user workflows.

### Gallery
> *Replace the image filename below with the screenshot that matches this dashboard*
![Care Management Call Stats Tab](assets/images/IMG_1527.jpeg)

---
### 🛠 Technical Toolkit Demonstrated
* **BI Platforms:** Power BI Desktop & Service
* **Languages & Analytics:** DAX (Time Intelligence, rolling offsets, dynamic dimensions), Advanced Excel, SQL
* **Core Competencies:** Healthcare Operations, Population Health Analytics, Data Modeling, UI/UX Design, SLA Compliance Monitoring
