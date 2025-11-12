# 🚛 Logistical Transport Power BI Dashboard

# 📊 Project Overview

This project focuses on analyzing and optimizing logistics and transport operations using Power BI. The objective is to provide actionable insights into transportation efficiency, fuel consumption, and delivery performance to enhance cost management and operational decision-making.

# 🎯 Problem Statement

Logistics companies face challenges in balancing cost efficiency, on-time delivery, and fuel optimization.
This project aims to:
Identify factors influencing transport cost and efficiency.
Monitor key performance metrics such as Fuel Efficiency, Cost per KM, and On-Time Delivery %.
Enable data-driven decision-making through an interactive Power BI dashboard.

# 🧩 Data Cleaning & Modeling
Performed data preprocessing to ensure data accuracy and usability for analysis.
 # Key steps included:
Handling missing and inconsistent data.
Creating relationships between transport, vehicle, and delivery datasets.
Building a data model optimized for performance in Power BI.

# 🧮 DAX Measures
Custom DAX measures were developed to calculate essential KPIs:

1️⃣ Fuel Efficiency
Fuel Efficiency = DIVIDE(SUM(FuelUsed), SUM(DistanceTravelled))

2️⃣ On-Time Delivery %
On Time Delivery % = DIVIDE(COUNT(OnTimeDeliveries), COUNT(TotalDeliveries)) * 100

3️⃣ Cost Per KM
Cost Per KM = DIVIDE(SUM(TotalCost), SUM(DistanceTravelled))

# 📈 Visualizations
The dashboard includes a variety of visuals for comprehensive insights:

# 📊 Bar Chart
Comparison of cost, distance, and delivery performance by region or vehicle type.

# 📉 Line Chart
Trends in cost and efficiency over time.

# 🔢 KPI Cards
Key metrics displayed prominently:

1️⃣Fuel Efficiency

2️⃣Cost per KM

3️⃣On-Time Delivery %

# 🗺️ Map Visual
Geographic distribution of deliveries and cost by region.

# 🧭 Dashboard Overview
An interactive Power BI Dashboard combining all visuals for a unified transport performance analysis.
Users can filter by region, vehicle type, time period, and driver to gain targeted insights.

# 🛠️ Tools & Technologies
Power BI for visualization and dashboarding
Excel / CSV for raw data
DAX for calculated measures and KPIs
Power Query for data transformation

# 📚 Key Insights
Identified high-cost regions for targeted optimization.
Measured fuel efficiency variations across routes.
Highlighted delivery delays impacting customer satisfaction.
Delivered real-time monitoring of transport KPIs.

# 💡 Outcome
This Power BI model provides a data-driven framework to:
Enhance operational efficiency
Reduce fuel and delivery costs
Improve service reliability.
