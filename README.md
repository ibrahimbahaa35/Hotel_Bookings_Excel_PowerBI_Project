# Hotel Booking Analysis Dashboard

## Overview
This repository contains a comprehensive data analytics project focused on analyzing hotel booking trends, customer behavior, and cancellation patterns. The interactive Power BI dashboard provides actionable insights into revenue generation, guest demographics, and operational metrics for both City and Resort hotels across multiple years (2015–2017).

## Repository Structure
* **`Hotel Bookings (Raw Data).csv`**: The original, unprocessed dataset containing historical hotel reservation records.
* **`Hotel Booking (Modified).xlsx`**: The cleaned and transformed dataset prepared for relational data modeling and visualization.
* **`HotelReservationProject.pbix`**: The main Power BI report file containing the data model, DAX measures, and interactive dashboards.
* **`PowerBI.mp4`**: A video demonstration showcasing the dashboard's interactivity, bookmark navigation, and features.

## Dashboard Architecture

The Power BI report is divided into three primary interactive pages, navigable via a custom-built home menu:

### 1. General View
Provides a high-level summary of hotel performance, room assignments, and guest demographics.
* **Key Performance Indicators (KPIs):** Average Booking Revenue ($357.85), Total Average Daily Rate (12.16M), Number of Guests (235K), Assigned Rooms Count (119K).
* **Visualizations:**
  * Top 5 Countries Visiting the Hotel (Donut Chart: Portugal, United Kingdom, France, Spain, Germany).
  * Total Assigned Rooms By Month (Line Chart for seasonality trends).
  * Booking Behavior By Distribution Channel (Bar Chart).
  * Hotel Type Breakdown (City Hotel vs. Resort Hotel).
* **Interactive Features:** Slicers for Year (2015, 2016, 2017) and Company Type. Custom bookmarks for toggling between "2015 View", "General View", and "Individual Company View".

### 2. Customer Insights
Delves deep into guest preferences, stay durations, and market segmentation.
* **KPIs:** Average Stay Week Nights (2.50), Average Stay Weekend Nights (0.93), Number of Repeated Guests (4K), Average Special Requests (57.14%).
* **Visualizations:**
  * Most Common Meal Types.
  * Best type of customer based on daily rate (Transient, Transient-Party, Contract, Group).
  * ADR (Average Daily Rate) vs. Special Requests by Customer Type.
  * Customer Lead Time vs. Cancellation Behavior.
* **Interactive Features:** Filters for Arrival Date (Year, Month) and specific Market Segments.

### 3. Booking & Cancellation
Focuses on reservation outcomes, cancellation rates, and financial impact.
* **KPIs:** Total Bookings (119K), Total Cancellations (44K), Cancellation Rate (37.04%), Lost Revenue ($16.73M).
* **Visualizations:**
  * Total Bookings Based on Market and Company Types.
  * Booking Volume by Status Breakdown (Waterfall Chart: Check-Out, Canceled, No-Show).
  * Top 3 Countries Based On Cancellation Rate (Gauge/Donut visuals).
* **Interactive Features:** Filters for Arrival Date Year and Hotel Type (City/Resort).

## Technologies Used
* **Data Exploration & Cleaning:** Microsoft Excel, Power Query
* **Data Modeling & Visualization:** Microsoft Power BI
* **Metrics Calculation:** DAX (Data Analysis Expressions)

## How to Use
1. Download the `HotelReservationProject.pbix` file.
2. Open the file using Power BI Desktop.
3. Use the custom navigation buttons on the landing page to explore the *General View*, *Customer Insights*, and *Booking & Cancellation* dashboards.
4. Interact with the filters (Year, Market Segment, Hotel Type) or click on specific visual elements to cross-filter the data dynamically.
