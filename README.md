# supply-chain-risk-intelligence-powerbi
1. PROJECT OVERVIEW (Start Here)
👉 Read this first:
I built a Supply Chain Risk Intelligence dashboard in Power BI to analyze shipment delays, identify high-risk suppliers and countries, and support decision-making.
The dashboard includes KPIs, trend analysis, geographic insights, supplier risk ranking, drill-through for deep analysis, and a what-if simulation feature.

2. Short Description
👉 Key points:
An interactive Power BI dashboard to analyze shipment delays, identify high-risk suppliers and regions, and simulate performance improvements using what-if analysis.

3. KEY FEATURES
## Key Features

- KPI tracking: Total Shipments, Delay %, Avg Delay, High Risk Shipments  
- Trend analysis using rolling averages  
- Country and supplier risk ranking (Top N filtering)  
- Drill-through for supplier-level deep dive  
- What-if analysis for scenario simulation  
- Dynamic insight generation using DAX  

NOTE: Delay % is used instead of raw counts to normalize performance across different volumes.


4. DATA MODEL
## Data Model

The project uses a structured data model with:
- Fact table: Shipment data  
- Dimension tables: Supplier, Country, Date  
- Additional datasets: Weather and geopolitical risk  

A star schema approach ensures efficient filtering and scalability.

5. DAX HIGHLIGHTS
## DAX Highlights

- Delay % for normalized performance evaluation  
- Rolling Delay % for trend smoothing  
- CALCULATE for conditional aggregation  
- DATEADD for time-based comparison  
- SELECTEDVALUE for what-if simulation  


6. DASHBOARD PAGES
## Dashboard Overview

### Page 1: Executive Overview
- KPI summary  
- Delay trends  
- Geographic and supplier risk analysis  

### Page 2: Supplier Performance Deep Dive
- Supplier-specific KPIs  
- Delay and shipment trends  
- Detailed performance analysis  


7. BUSINESS IMPACT
## Business Impact

This dashboard helps:
- Identify high-risk suppliers and regions  
- Monitor performance trends over time  
- Support data-driven decision-making  
- Simulate improvement scenarios 

8.BUSINESS VALUE

👉 What dashboard helps with:

Identify risky suppliers
Identify high-delay regions
Track performance trends
Simulate improvements



9. SCREENSHOTS SECTION
    <img width="1177" height="661" alt="image" src="https://github.com/user-attachments/assets/a513c6ac-bb16-476b-b9ec-d24ecfd39671" />
   <img width="1086" height="622" alt="image" src="https://github.com/user-attachments/assets/73cbfad7-3636-4a12-887a-6e2da7f2d978" />
<img width="1086" height="622" alt="image" src="https://github.com/user-attachments/assets/3241e986-35fe-488c-8cd6-c3e5ca0e0fb3" />

