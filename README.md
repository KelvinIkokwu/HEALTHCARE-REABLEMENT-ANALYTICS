# Healthcare Reablement & Discharge Analytics Dashboard

## Overview
This project is a comprehensive Power BI solution designed for NHS-aligned reablement and discharge services. It provides operational insights to hospital discharge teams and care providers, helping them allocate care packages efficiently, monitor patient recovery, and optimize workforce allocation.

## Tools Used
- Microsoft Power BI
- SQL Server
- ETL Workflows
- Data Modelling
- Excel (for preprocessing and validation)

## Problem
Hospital discharge teams and care providers needed a way to:
- Track patient progress
- Compare planned vs delivered care times
- Monitor care visit completion
- Allocate staffing efficiently
- Understand referral response rates
- Analyse patient recovery trends

## Solution
Developed an integrated Power BI dashboard featuring:

- **Planned vs Delivered Care Times** – analyse discrepancies and optimize scheduling  
- **Care Visit Completion Stats** – track completed visits versus planned visits  
- **Care Capacity Analysis** – determine staffing needs (1 carer vs 2 carers)  
- **Hospital Referral Response Ratings** – monitor responsiveness of care providers  
- **Client Recovery Progress (RAG Status)** – classify patients as Red, Amber, or Green for ongoing care needs  
- **Client Demographics & Geographics** – map-based visualisation for regional planning  
- **User Reablement Goals Tracker** – monitor individual patient goal achievement over 6-week reablement packages  
- **KPI Tracker** – consolidate key metrics for operational oversight  

## Repository Structure
- `Data/` → Sample anonymized CSV datasets used for dashboard demonstration  
- `Dashboards/` → Power BI dashboard files (.pbix)  
- `ETL/` → SQL scripts and ETL workflow documentation  
- `Screenshots/` → Images of dashboards and data model  
- `Insights/` → Markdown file summarizing insights generated from analysis

## Screenshots

1. **Dashboard Overview**  
   ![Dashboard Overview](Screenshots/Dashboard_Overview.png)  
   Full overview showing all KPIs at a glance.

2. **Care Times Analysis per Service User**  
   ![Care Times Analysis](Screenshots/Care_Times_Analysis_Per_Service_User.png)  
   Planned vs delivered care times per patient.

3. **KPI Tracker**  
   ![KPI Tracker](Screenshots/KPI_Tracker.png)  
   Consolidated key performance indicators for care visits, staff response, and patient outcomes.

4. **Reablement Data Metrics**  
   ![Reablement Data Metrics](Screenshots/Reablement_Data_Metrics.png)  
   Aggregated metrics including demographics, recovery progress, and service delivery stats.

5. **Reablement Duration Analysis**  
   ![Reablement Duration Analysis](Screenshots/Reablement_Duration_Analysis.png)  
   Duration of reablement services per patient to identify trends and resource needs.

6. **User Reablement Goals Achievement Tracker**  
   ![User Reablement Goals](Screenshots/User_Reablement_Goals_Achievement_Tracker.png)  
   Tracks progress toward patient reablement goals.

7. **Hospital Referral Response Rating**  
   ![Hospital Referral Response Rating](Screenshots/Hospital_Referral_Response_Rating.png)  
   Visualizes referral response times and their impact on discharge.

8. **Data Model & Architecture**  
   ![Data Model Architecture](Screenshots/Data_Model_Architecture.png)  
   Shows tables, relationships, and ETL workflow feeding the dashboard.

## Key Insights Generated
- Average care visit duration exceeded planned time by 18%, highlighting resource planning gaps.  
- Patients classified as Amber RAG status showed the highest improvement rates during reablement.  
- Providers with referral response times under 2 hours facilitated faster patient discharge.  
- Care staffing requirements aligned with actual demand, improving operational efficiency.

## How to Use
1. Download the `.pbix` file from `Dashboards/`.  
2. Open in Power BI Desktop to explore visualizations and filters.  
3. View `Data/` CSV files for sample datasets.  
4. Check `ETL/` for SQL scripts and workflow documentation.  
5. Review insights in `Insights/` folder for interpretation guidance.

## Impact
This dashboard has enhanced decision-making for care providers, improved operational visibility, and supported efficient patient discharge planning. It demonstrates full-cycle BI capabilities: **Data Extraction → Transformation → Modelling → Dashboard → Insights**.
