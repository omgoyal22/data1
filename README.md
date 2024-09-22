**Hotel Performance Insights using Power BI
Overview
This Power BI project analyzes hotel operations using various metrics derived from hotel booking data. The analysis helps assess hotel performance across multiple dimensions, such as total revenue, occupancy percentage, and weekend trends. The project emphasizes key performance indicators (KPIs) critical for the hotel industry, including Revenue per Available Room (RevPAR), Average Daily Rate (ADR), and Occupancy Rate (OCC).

Project Objectives
Analyze key hotel metrics such as revenue, occupancy, and room utilization.
Provide insights into weekend occupancy trends, especially on Fridays and Saturdays, with check-outs typically occurring on Sunday mornings.
Handle booking anomalies, including no-shows and booking refunds, and assess their financial impact.
Dataset Description
The dataset contains the following key attributes:

Guest ID: Unique identifier for each guest.
Property ID: Unique identifier for each property.
Booking Date: The date on which the booking was made.
Check-in/Check-out Dates: The dates of guest arrival and departure.
Number of Guests: The total number of guests for each booking.
Room Category: The type/category of room booked (e.g., standard, deluxe, suite).
Booking Category: Type of booking (e.g., online, direct, corporate).
Booking Status: Whether the booking was confirmed, canceled, or no-show.
Key Metrics
1. Revenue per Available Room (RevPAR)
A key performance metric to assess how much revenue each available room generates.
Formula: Total Revenue / Total Available Rooms.
RevPAR considers only the rooms available for booking, excluding rooms that are out of service due to maintenance issues like plumbing.
2. Average Daily Rate (ADR)
Measures the average rate at which rooms are sold per day.
Formula: Total Room Revenue / Number of Rooms Sold.
When occupancy reaches 100%, ADR and RevPAR values will be equal.
3. Occupancy Rate (OCC)
Shows the percentage of rooms that are occupied.
Formula: Total Rooms Occupied / Total Available Rooms.
4. Weekend Occupancy
Focuses on Friday and Saturday bookings, as these are peak days in the hotel industry. Most guests check out on Sunday morning to prepare for the workweek.
Additional Metrics
SRN (Sellable Room Nights): The number of rooms that are available for sale on a given night.
DSRN (Daily Sellable Room Nights): The number of rooms available for sale per day.
URN (Utilized Room Nights): The total number of nights that rooms are occupied.
BRN (Booked Room Nights): The total number of nights booked by guests.
Realization: Measures room utilization efficiency.
Formula: URN / BRN.
Handling No-Shows and Refunds
No-Show: A booking is confirmed but the guest does not check in.
Financial impact:
If the guest pays upfront, there is no loss.
If the guest pays upon check-in, the no-show results in a revenue loss.
Refund policies (e.g., 100% refund for online bookings) can also lead to financial loss if no revenue is generated despite the booking.
Insights Provided
Revenue Analysis: Track monthly, weekly, and daily revenues.
Occupancy Trends: Identify peak days, such as weekends, and measure overall occupancy.
Room Utilization Efficiency: Monitor how effectively the hotel utilizes its rooms, accounting for booked vs. utilized nights.
Project Tools
Power BI: For creating dashboards, visualizing data, and generating insights.
Excel/CSV: Used as the primary data source, containing the hotel’s booking and revenue data.
**
