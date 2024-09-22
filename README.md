Hotel Performance Insights using Power BI
Problem Statement: The dataset contains comprehensive information on a hotel’s operations, including guest IDs, property IDs, booking dates, check-in and check-out dates, the number of guests, room categories, booking categories, and booking statuses. Using this data, we have created key performance metrics such as total revenue and occupancy percentages, broken down by month and week.

In the hotel industry, Fridays and Saturdays are peak occupancy days, with most guests checking out on Sunday morning, as many prefer not to stay Sunday night due to work commitments on Monday.

Our analysis focuses on the following key metrics:

REVPAR (Revenue per Available Room)
ADR (Average Daily Rate): Calculated as total room revenue divided by the number of rooms sold.
OCC (Occupancy Rate): Total rooms occupied divided by total rooms available.
Key observations:

When occupancy is 100%, the ADR and REVPAR values will be equal.
REVPAR accounts for the number of available rooms, excluding rooms that are out of service (e.g., due to plumbing issues).
Additional metrics:

SRN (Sellable Room Nights)
DSRN (Daily Sellable Room Nights)
URN (Utilized Room Nights)
BRN (Booked Room Nights)
Realization: Calculated as URN/BRN, showing how many booked rooms were actually utilized.
We also address scenarios like no-shows, where guests either pay upfront or opt for a 100% refundable booking. In cases where guests don’t show up and payment is handled at the hotel or through refundable booking, it may result in potential losses.
