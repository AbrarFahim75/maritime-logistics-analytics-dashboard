# Maritime Logistics Analytics Dashboard

A Power BI project analyzing maritime terminal performance, cargo movement efficiency, and operational bottlenecks.

---

## Project Overview

This project focuses on evaluating terminal operations using data-driven insights. It provides visibility into cargo movement performance and supports decision-making in logistics and supply chain environments.

---

## Key Features

- KPI tracking: Total Movements, On Target %, At Risk %, Bottleneck %, Avg Duration, Unique Vessels  
- Terminal-level performance analysis  
- Vessel category comparison  
- Monthly trend analysis for bottlenecks  
- Interactive filtering by vessel category, performance band, and regional hub  

---

## Data Model

The dashboard is built using a star schema:

- fact_cargo_movements  
- dim_terminal  
- dim_vessel  
- dim_time  

---

## Tools & Technologies

- Power BI  
- DAX  
- Data Modeling  

---

## Dashboard Preview

![Dashboard Preview](images/dashboard-preview.png)

---

## Key Insights

- Bottleneck movements represent a significant portion of operations  
- Performance varies across terminals and vessel categories  
- Data highlights areas for process improvement and optimization  

---

### KPI & Terminal Performance View

![KPI Analysis](images/kpi-performance-analysis.png)

## Project Structure

```
maritime-logistics-analytics-dashboard/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── dashboard/
│   └── Maritime.pbix
│
├── images/
│   └── dashboard-preview.png
│
├── docs/
│   └── project-report.md
│
├── README.md
```

---

## Example DAX Calculations

```DAX
Delay Ratio = DIVIDE([Delayed Shipments], [Total Shipments])

Port Efficiency Score = 
1 - DIVIDE([Avg Delay Time], [Max Delay Time])
```

---

## Business Impact

- Enables identification of inefficient ports and operational bottlenecks  
- Supports data-driven decision-making in logistics planning  
- Helps reduce delays and improve supply chain efficiency  

---

## How to Use

1. Download the `.pbix` file  
2. Open it in Power BI Desktop  
3. Use filters and visuals to explore insights  

---

## Author

Md Abrar Fahim  
B.Sc. Information Engineering – HAW Hamburg 
