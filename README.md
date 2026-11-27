# 🚖 Uber Ride Booking Analytics

### Ride Smarter. Travel Better.

An end-to-end data analytics project focused on analyzing ride bookings, customer behavior, vehicle performance, cancellations, revenue, and ride trends using Python, SQL, and Power BI.

---

## 📌 Project Overview

The objective of this project is to analyze ride-booking data and generate meaningful business insights.

The project explores booking patterns, ride completion rates, cancellation behavior, vehicle preferences, payment methods, customer ratings, and revenue generated from completed rides.

By combining data cleaning, exploratory data analysis, SQL queries, and interactive dashboards, this project aims to transform raw booking data into actionable insights.

---

## 🎯 Project Objectives

- Analyze overall ride-booking performance.
- Identify completed and cancelled bookings.
- Understand customer and driver cancellation patterns.
- Analyze vehicle-type preferences.
- Evaluate booking trends by day and hour.
- Identify popular pickup locations.
- Analyze payment method distribution.
- Calculate revenue from completed rides.
- Understand customer ratings and ride distances.
- Build an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| SQL (MySQL) | Data querying and analysis |
| Power BI | Interactive dashboard development |
| GitHub | Project documentation and version control |

---

## 📂 Dataset Information

The dataset contains **150,000 ride-booking records** with 21 columns.

### Dataset Columns

- Date
- Time
- Booking ID
- Booking Status
- Customer ID
- Vehicle Type
- Pickup Location
- Drop Location
- Avg VTAT
- Avg CTAT
- Cancelled Rides by Customer
- Reason for Cancelling by Customer
- Cancelled Rides by Driver
- Driver Cancellation Reason
- Incomplete Rides
- Incomplete Rides Reason
- Booking Value
- Ride Distance
- Driver Ratings
- Customer Rating
- Payment Method

**Dataset Period:** January 2024 – December 2024

---

## 📊 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Bookings | 150,000 |
| Completed Rides | 93,000 |
| Completion Rate | 62% |
| Cancelled by Driver | 27,000 |
| Cancelled by Customer | 10,500 |
| No Driver Found | 10,500 |
| Incomplete Rides | 9,000 |
| Completed Booking Value | ₹47,260,574 |
| Average Completed Ride Distance | 26.00 |
| Average Customer Rating | 4.40/5 |

*Financial and ride-distance KPIs are calculated using completed rides. The distance unit is not specified in the dataset.*

---

## 🔍 Key Analysis

### 1. Booking Performance Analysis
- Total booking analysis.
- Completed versus unsuccessful bookings.
- Booking status distribution.
- Overall ride completion rate.

### 2. Vehicle Type Analysis
- Booking distribution by vehicle type.
- Comparison of vehicle preferences.
- Identification of popular vehicle categories.

### 3. Revenue Analysis
- Total booking value from completed rides.
- Revenue trends.
- Average booking value.

### 4. Cancellation Analysis
- Customer cancellation patterns.
- Driver cancellation patterns.
- Reasons behind ride cancellations.
- Incomplete ride analysis.

### 5. Time-Based Analysis
- Monthly booking trends.
- Hourly booking distribution.
- Identification of peak booking hours.

### 6. Customer Analysis
- Customer rating distribution.
- Average customer ratings.
- Ride distance analysis.

### 7. Location Analysis
- Top pickup locations.
- Booking distribution across pickup locations.

### 8. Payment Analysis
- UPI transactions.
- Cash payments.
- Credit and debit card payments.
- Uber Wallet transactions.
- Missing payment information.

---

## 💡 Key Business Insights

1. The dataset contains 150,000 bookings, of which 93,000 were completed.
2. The overall completion rate is 62%.
3. Driver cancellations account for 18% of all bookings.
4. Customer cancellations account for 7% of all bookings.
5. Another 7% of bookings had no driver found.
6. Completed rides generated approximately ₹4.73 crore in booking value.
7. The average customer rating for completed rides is approximately 4.40 out of 5.
8. UPI is the most frequently recorded payment method.

---

## 📈 Dashboard

The interactive dashboard provides:

- Total booking KPIs.
- Completed ride analysis.
- Booking status distribution.
- Vehicle-type performance.
- Monthly booking trends.
- Hourly booking trends.
- Top pickup locations.
- Payment method distribution.
- Ride distance distribution.
- Customer rating analysis.

### Dashboard Preview
<img width="1320" height="738" alt="Screenshot 2026-11-27 150335" src="https://github.com/user-attachments/assets/0f2d8802-0371-4cbd-9b2b-e9853fba01ac" />



## 📁 Project Structure


Uber-Ride-Booking-Analytics/
│
├── README.md
│
├── dataset/
│   └── uber_ride_bookings.csv
│
├── python_analysis/
│   ├── data_cleaning.py
│   └── exploratory_data_analysis.py
│
├── sql/
│   └── uber_ride_analysis.sql
│
├── powerbi/
│   └── uber_ride_dashboard.pbix
│
├── dashboard/
│   └── Uber_Ride_Booking_Dashboard.html
│
├── insights/
│   └── business_insights.md
│
├── dashboard_preview.png
│
├── LICENSE
│
└── .gitignore
