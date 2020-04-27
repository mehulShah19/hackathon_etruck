# hackathon_etruck

To run the code; download the data from the location https://drive.google.com/file/d/1iQfIBbIYHVWC5dyj3dkiWVleALginNu8/view?usp=sharing

Also, download the first week trip data on the same folder

The clustered_charging_stations.csv contains = Latitude, Longitude of charging stations. It also has information  *count(Number of times a truck passed this node)*

To calculate number of charging port;  
no_of_charging_port = one_day_visits * 0.60 / 14

14 = Assuming charging stations are operated for 20 hours and each truck takes 1 and half hour
0.60 = Assuming around 60% of the route traffic is handled by this node. Remember we have charging stations every 85-115 miles
