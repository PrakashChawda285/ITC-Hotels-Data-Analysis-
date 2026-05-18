# ITC-Hotels-Data-Analysis-

ITC Hotels Revenue Optimization & Business Intelligence Dashboard
[A].Project Overview

This project focuses on building an interactive Power BI dashboard for ITC Hotels to analyze hotel performance, occupancy trends, booking behavior, and cancellation patterns. The dashboard transforms raw hotel booking data into meaningful business insights that help management make data-driven decisions.

The solution provides real-time analytical views across financial performance, room category trends, occupancy rates, and revenue leakage caused by booking cancellations.

[B].Problem Statement

ITC Hotels operates multiple hotel properties across different cities and room categories. However, management lacked a centralized analytics platform to monitor business performance efficiently.

[C].Key challenges included:

No real-time revenue monitoring
Limited occupancy visibility
Untracked cancellation losses
No clear understanding of room category performance
Dependence on fragmented reports


[D].Objectives


Build a comprehensive Power BI dashboard
Track revenue KPIs and growth metrics
Analyze occupancy trends
Evaluate booking behavior
Quantify cancellation losses
Enable self-service analytics using slicers and filters
Dashboard Features
Financial Analysis
Total Revenue
ADR (Average Daily Rate)
RevPAR
Moving Average Revenue
MoM & WoW Growth
Occupancy Analysis
Occupancy Rate
Arrived Customers
Hotel-wise occupancy trends
Weekday vs Weekend analysis
Booking Insights
Average Length of Stay (ALOS)
Lead Time Analysis
Room Category Performance
Booking Distribution
Cancellation Analysis
Cancellation Rate
Lost Revenue
Cancellation Growth Trends
Revenue Leakage Analysis
Dataset Information
Feature	Details
Hotels Covered	7 Properties
Time Period	May – July 2022
Records	233K+ Customers
Cities	Agra, Bangalore, Delhi, Goa, Hyderabad & more
Room Categories	RT1, RT2, RT3, RT4
Hotel Types	Business & Luxury
Tools & Technologies Used
Power BI
Power Query
DAX
Data Modeling
Microsoft Excel
Key DAX Measures
Total Revenue = SUM(Bookings[Revenue])

ADR = DIVIDE([Total Revenue], [Room Nights Sold])

RevPAR = DIVIDE([Total Revenue], [Total Available Room Nights])

Occupancy Rate = DIVIDE([Arrived Customers], [Total Customers])

Cancellation Rate = DIVIDE([Cancelled Bookings], [Total Bookings])


[E].Project Workflow


Data Collection
Data Cleaning using Power Query
Data Modeling (Star Schema)
DAX Measure Creation
Dashboard Development
KPI Validation
Final Visualization & Insights


[F].Key Insights

Total Revenue exceeded ₹2 Billion
Cancellation losses reached ₹299 Million
Occupancy Rate remained around 57.87%
Elite rooms generated the highest revenue
June showed a noticeable revenue dip
Cancellation growth increased by 40% MoM


[G].Recommendations


Introduce stricter cancellation policies
Improve weekend occupancy with offers
Promote low-performing hotels
Increase upselling for Elite room categories
Build predictive analytics for demand forecasting
Future Enhancements
Real-time dashboard refresh
Predictive forecasting using Python/R
Customer segmentation analysis
Dynamic pricing engine
Automated cancellation alerts


[H].Folder Structure


ITC-Hotels-Dashboard/
│
├── Dataset/
├── Dashboard/
├── Screenshots/
├── Presentation/
├── README.md
└── ITC_Hotels.pbix


[I].Conclusion

This project demonstrates how Power BI can transform hotel booking data into actionable business intelligence. The dashboard helps stakeholders monitor KPIs, identify revenue leakage, and improve operational efficiency through data driven decision-making. 
