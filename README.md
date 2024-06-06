# Python_Hospitality-Data-Analysis
Hospitality Data Analysis

Atliq Grands is Hotel Chain, which operates in various cities in India: Delhi, Bangalore, Mumbai & Hyderabad.
They have different types of Hotels like: AtliQ Seasons, AtliQ Exotica, AtliQ Bay, AtliQ Palace and others
They also have different types of rooms like Standard, Elite, Premium, Presidential

A person can book a hotel, via various mediums: MakeYourTrip, Tripster, etc
The booking does to AtliQ Grands Database.

Problem Statement:
AtliQ is facing revenue losses from its competitors. They are losing their market share. So, they have hired a Data Analyst to identify certain insights.

Tables Provided:
1. fact_aggregated_bookings: Having all the successful booking data vs Capacity for each room
2. fact_bookings: Having transactional booking data with booking status, revenue realised, revenue generated
3. dim_rooms: Having all the rooms & it's category mentioned
4. dim_hotels: Having property name, category, city
5. dim_date: Having date, month, week number, weekend/weekday info
6. new_august_data: August Data provided at later stage

Analytics:
Hospitality Data Analysis
1. Analysing what is the average occupancy rate in each of the room categories.
2. Analysing average occupancy rate per city
3. Analysing when was the occupancy better. Weekday or Weekend?
4. In June, what is the occupancy for different cities?
5. Got new data for August. Could you add that to existing data?
6. Print revenue realized per city
7. Print month-by-month revenue
8. Print revenue realized per hotel type
9. Print average rating per city
10. Print a pie chart of revenue realized per booking platform

Steps:
1. Data Cleaning: Replacing Null Values like in the Capacity Column with Median, Removing Outliers
2. Data Transformations: Adding Columns like Occupancy Percentage, and Merging Datasets as per requirement
3. Insights Generations as asked.

Tech Stuff:
Pandas & its functions: shape,describe(),value_counts(), groupby(),merge(),sort_values(),info()

Snippets of Analysis
<img width="532" alt="image" src="https://github.com/DMSinha/Python_Hospitality-Data-Analysis/assets/101706831/aaecd8c9-cad0-4827-a74d-be6e781abfe0">

Revenue Realized Per Property
<img width="425" alt="image" src="https://github.com/DMSinha/Python_Hospitality-Data-Analysis/assets/101706831/87238955-7fde-4a8f-9efb-4517ea465cf8">

Occupancy % of Different Cities
<img width="431" alt="image" src="https://github.com/DMSinha/Python_Hospitality-Data-Analysis/assets/101706831/3448adbe-1974-4b17-836b-7d07e0d6327d">



