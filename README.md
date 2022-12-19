# Cyclistic-Queries
A junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. Determining the difference between "casual" riders and "member" riders.

The following data was provided by Motivate International Inc. (https://www.divvybikes.com/data-license-agreement)
202201-divvy-trip-data,
202202-divvy-trip-data,
202203-divvy-trip-data,
202203-divvy-trip-data,
202203-divvy-trip-data,
202203-divvy-trip-data,
202203-divvy-trip-data,
202203-divvy-trip-data,
202203-divvy-trip-data,
202203-divvy-trip-data,
202203-divvy-trip-data,
202203-divvy-trip-data

Total number of rows = 6,924,133
Raw data was cleaned in Excel.
- Confirmed no duplicates in ride_id column.
- Seperated and formatted date and time into seperate columns.
- Created day_of_week column, where Sunday = 1
- Calculated trip_duration and used "if" statement to correct negative trip durations.

Three questions will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

Questions were answered using SQL in the BigQuery data warehouse. 
