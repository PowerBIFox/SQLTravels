# SQLTravels Analytics Platform

## Overview

SQLTravels Transport Analytics Platform is an end-to-end Microsoft Fabric and Power BI analytics solution developed to simulate a large-scale interstate passenger transportation enterprise operating across multiple Indian states.

The project demonstrates modern data engineering, dimensional modeling, semantic modeling and business intelligence practices using Microsoft Fabric Lakehouse and Power BI. The solution enables operational, financial and executive reporting across bookings, trips, fleet utilization, route performance, fuel consumption, maintenance activities and branch operations.

---

## Business Scenario

Passenger transportation companies generate large volumes of operational and transactional data every day across routes, buses, drivers, branches, bookings and maintenance operations.

This project addresses key business questions such as:

* Which routes generate the highest revenue?
* Which routes operate at the highest occupancy?
* Which branches contribute the most bookings?
* Which buses incur the highest maintenance costs?
* How efficiently is fuel being utilized?
* How are booking channels and payment modes evolving over time?
* What seasonal patterns impact passenger demand?
* Which drivers consistently deliver better operational performance?

---

## Technology Stack

### Microsoft Fabric

* Lakehouse
* Delta Tables
* Semantic Model
* SQL Endpoint
* Git Integration

### Power BI

* Data Modeling
* DAX
* Time Intelligence
* KPI Reporting
* Interactive Dashboards

### Data Modeling

* Star Schema
* Bridge Table Design
* Fact and Dimension Modeling
* Semantic Layer Optimization

---

## Dataset Summary

| Metric             | Volume                                                                     |
| ------------------ | -------------------------------------------------------------------------- |
| Passenger Bookings | 2,000,000+                                                                 |
| Analysis Period    | 2021 - 2025                                                                |
| States Covered     | Karnataka, Andhra Pradesh, Telangana, Maharashtra, Goa, Gujarat, Rajasthan |
| Fact Tables        | 4                                                                          |
| Dimension Tables   | 9                                                                          |
| Bridge Tables      | 1                                                                          |
| Total Tables       | 14                                                                         |

---

## Semantic Model Structure

### Dimension Tables

* vrlt_dim_branch
* vrlt_dim_bus
* vrlt_dim_channel
* vrlt_dim_city
* vrlt_dim_date
* vrlt_dim_demand_event
* vrlt_dim_driver
* vrlt_dim_payment_mode
* vrlt_dim_route

### Bridge Table

* vrlt_bridge_route_stop

### Fact Tables

* vrlt_fact_booking
* vrlt_fact_trip
* vrlt_fact_fuel
* vrlt_fact_maintenance

---

## Analytics Domains

### Executive Analytics

* Revenue Performance
* Passenger Growth
* Occupancy KPIs
* Profitability KPIs
* Operational KPIs

### Booking Analytics

* Booking Trends
* Channel Performance
* Payment Mode Analysis
* Cancellation Analysis
* Advance Booking Patterns

### Route Analytics

* Route Profitability
* Route Occupancy
* Route Revenue Contribution
* Seasonal Route Performance

### Fleet Analytics

* Fleet Utilization
* Bus Performance
* Capacity Analysis
* Revenue per Bus

### Driver Analytics

* Driver Performance
* Driver Ratings
* Safety Indicators
* Fuel Efficiency Analysis

### Fuel Analytics

* Fuel Consumption Trends
* Fuel Cost Analysis
* Route-wise Fuel Utilization
* Fleet Fuel Performance

### Maintenance Analytics

* Maintenance Cost Tracking
* Breakdown Analysis
* Downtime Monitoring
* Fleet Reliability Metrics

### Branch Analytics

* Branch Revenue
* Passenger Volume
* Route Coverage
* Regional Performance

---

## Data Model Highlights

* Enterprise Star Schema Design
* One-to-Many Relationships
* Bridge Table for Route Stops
* Date Intelligence Enabled
* Multi-Fact Analytical Model
* Optimized Semantic Layer
* Git Enabled Source Control
* Fabric Native Architecture

---

## Key KPIs

### Commercial KPIs

* Total Revenue
* Revenue Growth %
* Average Fare
* Revenue per Route
* Revenue per Bus

### Operational KPIs

* Total Trips
* On-Time Performance %
* Delay Rate %
* Fleet Utilization %

### Customer KPIs

* Total Bookings
* Total Passengers
* Occupancy %
* Cancellation Rate %

### Cost KPIs

* Fuel Cost
* Maintenance Cost
* Operating Cost per Trip
* Profit Margin %

---

## Future Enhancements

* Real-Time Fleet Tracking
* GPS Route Monitoring
* Predictive Maintenance
* Demand Forecasting
* Dynamic Fare Optimization
* AI-Powered Operational Insights
* Near Real-Time Reporting

---

## Repository Contents

* Semantic Model
* Data Model Documentation
* DAX Measures
* Power BI Reports
* Dashboard Screenshots
* Architecture Diagrams

---

## Author

Ravi Kamana

Senior Data Engineer | Microsoft Fabric Consultant | Power BI Specialist | Microsoft Certified Trainer (MCT)

Certifications:

* Microsoft PL-300
* Microsoft DP-600
* Microsoft AI-102
* Microsoft Certified Trainer (MCT)

---

## Disclaimer

This project is a synthetic analytics solution created for demo, learning, portfolio, demonstration and consulting showcase purposes. No real customer, passenger, operational or financial data has been used.
