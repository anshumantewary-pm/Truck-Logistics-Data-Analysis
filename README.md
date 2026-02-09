#Travel Logistics Data – README

Overview
This dataset contains operational travel and logistics information used to monitor, analyze, and improve transportation performance. It supports analysis related to trip tracking, delays, on-time performance, vehicle utilization, and route efficiency.
The data is suitable for use in Excel, SQL, Power BI, Python, or R for business analytics and logistics optimization.

#Purpose of the Dataset
The dataset is designed to help answer questions such as:
Are trips completed on time?
Where do delays occur most frequently?
How efficiently are vehicles utilized?
Are minimum daily distance targets being met?
How accurate are planned ETAs compared to actual ETAs?
Data Granularity
One row represents one logistics trip / booking
Time-based, vehicle-based, and route-based analysis is possible

#Key Data Categories
1. Booking & Trip Information

BookingID

BookingID_Date

Market / Regular

Trip Start Date

Trip End Date

Used to identify and group trips over time.

2. Vehicle Details

Vehicle Number

Vehicle Type

Minimum kms to be covered in a day

Used for fleet utilization and productivity analysis.

3. Location & Route Information

Origin Location

Destination Location

Origin Location Code

Destination Location Code

Origin Latitude & Longitude

Destination Latitude & Longitude

Used for route mapping, distance calculation, and geo-analysis.

4. Live Tracking & GPS Data

GPS Provider

Current Location

Current Latitude

Current Longitude

Data Ping Time

Used to track real-time movement and detect delays.

5. Time & Performance Metrics

Planned ETA

Actual ETA

On-time Indicator

Delay Indicator

Used to evaluate service-level performance.

6. Distance Metrics

Transportation Distance (in KM)

Used to analyze trip length, fuel efficiency, and cost estimation.

Common Use Cases

On-time vs delayed trip analysis

Delay root cause identification

Vehicle performance comparison

Route efficiency analysis

Daily minimum distance compliance

Logistics KPI dashboards

Recommended KPIs

On-Time Delivery Percentage

Average Delay Duration

Distance Covered per Vehicle per Day

Trip Completion Rate

ETA Accuracy

Data Quality Notes

Some records may have missing GPS pings

BookingID may not be unique in certain cases

Actual ETA may be blank for ongoing trips

Latitude/Longitude accuracy depends on GPS provider
