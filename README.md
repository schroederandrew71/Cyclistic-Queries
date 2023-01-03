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


Conclusions:
Annual member riders use cyclistic bikes primarily for weekday work commutes.  
Casual riders use bikes more on the weekends.  
Casual riders highest ride days are Friday, Saturday and Sunday.  
Casual riders increase rides as temperature increases.  
Meaning, the highest activity of casual bike rides comes during June, July, August.  Additionally, member riders do not use the docked bikes, only casual riders use this bike.  
Top 4 start stations and end stations of casual riders are along the waterfront.  

Casual riders would buy annual memberships and save money during the late spring, summer seasons and weekends.  

Cyclistic can use digital media to influence casual riders to become members by: 
1) advertising advantages to annual memberships leading up to and during summer months. 
2) Offering a membership plan with Lakeshore content.
3) Offering seasonal memberships may be advantageous to capturing casual riders who plan on riding during the summer months.

In addition to digital marketing, flyers and marketing material could be added to stations on Lakeshore Dr. during the summer months and at all docked bikes during the season.
