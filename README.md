# Maritime Logistics Performance Dashboard (Power BI + Analytics)

## Project Overview
This project analyzes maritime logistics and port performance using an interactive Power BI dashboard.  
The goal is to identify inefficiencies, delays, and operational bottlenecks in global shipping operations.

This project is inspired by a Data DNA challenge but independently rebuilt and enhanced with additional KPIs and analysis.

---

## Objectives
- Analyze port efficiency and turnaround time  
- Identify shipment delays and bottlenecks  
- Provide actionable insights for logistics optimization  
- Demonstrate business-oriented data storytelling  

---

## Tech Stack
- Power BI (Dashboard & Visualization)
- Power Query (Data Cleaning & Transformation)
- DAX (KPI Calculations)
- Optional: Python (Machine Learning extension)

---

## Dashboard Features
- Shipment trends over time  
- Port-wise performance comparison  
- Average turnaround time analysis  
- Delay distribution and patterns  
- Region-based filtering  

---

## Key KPIs
- Total Shipments  
- Average Turnaround Time  
- Delay Percentage  
- Port Efficiency Score (custom metric)  

---

## Key Insights
- Certain ports consistently show higher delays, indicating potential bottlenecks  
- Seasonal patterns affect shipment efficiency  
- High-volume ports are not always the most efficient  

---

## Enhancements (Beyond Original Video)
- Added Delay Ratio KPI  
- Designed Executive Summary Page  
- Improved dashboard layout and user experience  
- Created Port Efficiency Score using DAX  

---

## Dashboard Preview
![Dashboard Preview](images/dashboard_preview.png)

---

## Project Structure

```
maritime-logistics-dashboard/
│
├── data/
│   └── dataset.csv
│
├── dashboard/
│   └── maritime_dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
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

## Future Improvements (AI/ML Extension)

- Predict shipment delays using machine learning  
- Cluster ports based on performance  
- Implement anomaly detection for unusual delays  
- Deploy dashboard and model as a web application  

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
