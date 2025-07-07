# Ola Ride Cancellation & Performance Analysis Dashboard
An interactive Power BI dashboard built to uncover insights into ride cancellations, vehicle usage patterns, and customer-driver behavior based on 100,000+ simulated ride records in Bengaluru. This tool enables analysts to investigate key trends across booking status, ratings, vehicle types, and cancellation reasons.

# Short Description / Purpose
This Power BI project visualizes Ola ride data to explore cancellations by drivers and customers, analyze performance metrics, and assist stakeholders in identifying factors affecting ride success. It empowers decision-makers to improve ride experience and operational efficiency.

# Tech Stack
The dashboard was built using the following tools and technologies:

Power BI Desktop – Main tool for designing dashboards and visual storytelling.

Power Query – Used for data cleaning, merging, and shaping before analysis.

DAX – For calculated measures such as ride success rate, cancellation ratios, and rating averages.

SQL – To perform queries on booking success, cancellation reasons, ride distances, and more.

File Formats – .pbix for dashboard and .pdf for project scope documentation.

# Data Source
Synthetic dataset generated for Bangalore city, covering 1 month and ~100,000 records with the following fields:

Date & Time of Booking

Vehicle Type: Auto, Prime Sedan, Mini, Bike, Prime SUV, etc.

Pickup & Drop Locations (50 locations in Bengaluru)

Booking Status: Success, Cancelled by Customer, Cancelled by Driver

Cancellation Reasons by both parties (e.g., driver not moving, sick customer)

VTAT & CTAT: Vehicle/Customer Arrival Times

Ratings (Driver & Customer), Booking Value, Payment Method, Ride Distance

Status Split: ~62% Successful, <7% Cancelled by Customer, <18% Cancelled by Driver

# Features / Highlights
• Business Problem
Ride-hailing services face frequent cancellations and incomplete rides, resulting in poor customer experience and wasted operational capacity. Ola needs visibility into where, when, and why cancellations happen.

• Goal of the Dashboard
To deliver a decision-making dashboard that:
Analyzes cancellation patterns by time, reason, and geography.
Evaluates performance by vehicle type, ride distance, and ratings.
Highlights top-paying customers and high-performing drivers.
Supports strategic operations, driver allocation, and CX enhancement.

# Walkthrough of Key Visuals
Ride Volume Over Time
Line chart visualizing daily bookings and spikes during weekends or match days.

Booking Status Breakdown
Doughnut chart summarizing the ratio of successful vs. cancelled rides.

Top 5 Vehicle Types by Ride Distance
Bar chart showcasing which vehicles cover the most distance.

Average Customer Ratings by Vehicle Type
Column chart to compare customer satisfaction across categories.

Cancellation Reasons by Customer & Driver
Two bar charts breaking down reasons (e.g., driver asked to cancel, vehicle issue).

Revenue by Payment Method
Stacked bar chart to analyze revenue share by UPI, Cash, etc.

Top 5 Customers by Booking Value
Leaderboard visual listing high-spending customers.

Ride Distance Distribution
Histogram showing how far typical rides go, day-wise.

Driver Rating Distribution
Box plots comparing driver ratings across vehicle types.

Customer vs. Driver Ratings
Scatter plot showing rating correlations between riders and drivers.

Business Impact & Insights
Operational Optimization: Identify high-cancellation areas and time slots for better driver dispatching.

Customer Experience: Improve service where negative feedback or ride cancellations are frequent.

Revenue Monitoring: Pinpoint top contributors and optimize for high-value bookings.

CX Strategy: Reduce incomplete rides and boost ratings by understanding root causes.

# Screenshots / Demos
You can include in your GitHub: https://github.com/shivkanyam945/OLA-Analysis/blob/main/Ola%20Cancellation%20Analysis.png 
