# OLA-Analytics-Power-BI-Dashboard
A comprehensive Power BI analytics project designed to explore and visualize key performance metrics of OLA ride operations. This dashboard provides insights into bookings, cancellation patterns, vehicle performance, driver &amp; customer ratings, and revenue distribution across different OLA vehicle categories.

📌 Project Overview
This project analyzes an OLA rides dataset for the period selected by the user (via date slicer) and provides meaningful insights for business decision-making.
The dashboard is divided into multiple interactive pages:

Overall Analysis
Vehicle Type Performance
Revenue Insights
Cancellation Analysis
Ratings Dashboard

🛠️ Tools & Technologies Used
Power BI Desktop
Power Query for cleaning and transforming data
DAX Measures for KPIs & calculated fields
Excel/CSV dataset (custom dataset)

📊 Dashboard Pages & Key Insights
⭐ 1. Overall Analysis
KPIs Displayed
Total Bookings
Total Booking Value
Booking Status Distribution (Success, Canceled by Customer, Canceled by Driver, Driver Not Found)
Visuals Included
Pie Chart: Ride Volume by Booking Status
Line Chart: Ride Volume Trend Over Time
This page gives a complete snapshot of OLA’s operational performance for the selected time period.

🚗 2. Vehicle Type Analysis
This page provides a breakdown of performance by vehicle category:
Prime Sedan, Prime SUV, Prime Plus, Mini, Auto, Bike, E-Bike
Metrics Included
Total Booking Value
Success Booking Value
Average Distance Travelled
Total Distance Travelled
Helps understand which vehicle types generate maximum revenue and distance coverage.

💰 3. Revenue Insights
(Include if you have a revenue page — optional text below)
Provides a detailed view of revenue generated across different vehicle categories and timelines.
Includes KPIs, bar charts, and trend analysis.

❌ 4. Cancellation Analysis
This page explains cancellation behavior from both driver and customer perspectives.
KPIs
Total Bookings
Successful Bookings
Canceled Bookings
Cancellation Rate

Visuals
Pie Chart: Cancellation by Customer (with specific reasons)
Pie Chart: Cancellation by Driver (with specific reasons)
Helps identify operational issues and improve customer/driver experience.

⭐ 5. Ratings Dashboard
Displays Avg Driver Ratings and Avg Customer Ratings for each vehicle category.
Vehicle categories analyzed:
Prime Sedan
Prime SUV
Prime Plus
Mini
Auto
Bike
E-Bike
Provides insight into service quality and customer satisfaction.

📂 Project Structure
📁 OLA-Analytics-Dashboard
│── 📄 OLA_Dashboard.pbix
│── 📄 README.md
│── 📊 dataset.xlsx / dataset.csv
│── 📁 screenshots
│      ├── overall_page.png
│      ├── vehicle_type_page.png
│      ├── cancellation_page.png
│      ├── ratings_page.png
│      └── revenue_page.png

🎯 Business Impact
This dashboard helps stakeholders:
Identify top-performing vehicle categories
Monitor booking trends
Reduce cancellation rates through insight-driven decisions
Improve customer satisfaction
Track revenue & distance metrics
Evaluate driver performance
