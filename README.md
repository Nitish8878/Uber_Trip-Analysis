# Uber_Trip-Analysis
This Uber Trip Analysis project leverages Power BI to visualize and understand patterns in Uber ride data. The main objective is to uncover insights into ride frequency, peak hours, popular pickup locations, and operational efficiency. By transforming raw trip data into interactive dashboards.

## TABLE - TRIP DETAILS

## Dataset Used
<a herf ="https://github.com/Nitish8878/Uber_Trip-Analysis/blob/main/Uber%20Trip%20Details.xlsx"> Uber Trip Details </a>

The Trip Details table contains information on individual Uber rides, including trip timing, distance, fare details, and vehicle type. It helps analyze ride trends, peak hours, and revenue patterns. The Location Table maps numeric location IDs to actual area names, enabling pickup and drop-off location analysis
Trip ID-A unique identifier assigned to each Uber trip. This helps in tracking individual rides. 

Pickup Time - The exact date and time when the passenger was picked up. This is useful for analyzing trip trends, peak hours, and total ride duration.

Drop Off Time The exact date and time when the passenger was dropped off. Used to calculate trip duration and analyze trip completion trends.

Passenger Count - The number of passengers in the trip. Helps in understanding ride-sharing patterns and demand for different vehicle types.

Trip Distance - The distance covered during the trip, typically measured in miles. Used for fare calculation, efficiency analysis, and identifying long or short trips.

PULocationID (Pickup Location ID) - A numerical code representing the pickup location. It is linked to a location table to get the actual name of the pickup area.

DOLocationID (Drop Off Location ID) - A numerical code representing the drop-off location. This is used for destination analysis, ride patterns, and demand forecasting. 

Payment Type - The mode of payment used for the trip (e.g., credit card, cash, wallet). Helps in financial analysis and understanding customer preferences. 

Fare Amount - The base fare charged for the trip before any additional fees. This is essential for revenue analysis and pricing strategy. 

Surge Fee - The extra charge applied during high-demand periods. Helps in understanding surge pricing patterns and peak-hour demand. 

Vehicle-The type of Uber service used (e.g. UberX, UberXL, Uber Black). Used for analyzing vehicle demand and customer preferences. 


## TABLE LOCATION TABLE 

The Location Table contains a unique LocationID for each area, mapping it to its corresponding Location name and City. This table helps in analyzing trip patterns by identifying the most frequent pickup and drop-off locations. It also supports geographic-based insights and trends in ride demand.
 
LocationID-A unique identifier for each location in the dataset. It serves as a key to link locations to trips.

Location - The name of the area or neighborhood where pickups and drop-offs occur.

City - The city in which the location exists, helping in geographic segmentation and analysis.
