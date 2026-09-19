

📘 Task 4 – Traffic Accident Data Analysis
📌 Objective
Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day.
Visualize accident hotspots and contributing factors.

📂 Dataset Description
The dataset (task_4dataset.csv) contains 20 rows with the following columns:

1.id → Accident ID

2.date, time → Date and time of accident

3.location → Road/area where accident occurred

4.road_condition → Dry/Wet

5.weather → Clear/Rain/Fog

6.severity → Minor/Moderate/Severe

7.vehicle_type → Car, Bike, Truck, Bus

8.num_vehicles_involved → Number of vehicles in accident

9.num_injuries → Number of injuries

10.num_fatalities → Number of fatalities

11.speed_limit → Speed limit at location

12.lighting_condition → Daylight, Night, Streetlights

13.police_report → Yes/No

14.alcohol_involved → Yes/No

⚙️ Steps Implemented
Data Loading

>Uploaded and loaded dataset using pandas.

>Preprocessing

>Combined date and time into a datetime column.

>Extracted hour and categorized into time_of_day (Morning, Afternoon, Evening, Night).

>Pattern Analysis

>Accident counts by road condition, weather, and time of day.

Accident severity distribution.

1.Visualization

2.Bar charts for accidents by road condition, weather, time of day.

3.Accident hotspots by location.

4.Severity by vehicle type.

5.Alcohol involvement and police reports.

📊 Output Summary
Road Condition: Dry (12), Wet (8)

Weather: Clear (8), Rain (8), Fog (4)

Time of Day: Evening (8), Morning (6), Afternoon (6), Night (0)

Hotspots: Multiple accidents at Highway 44, City Center, Highway 9, Market Road, Airport Road.

Contributing Factors:

Alcohol involvement present in several severe cases.

Police reports filed for most severe accidents.

Trucks and buses linked to higher injury counts.

✅ Conclusion
This project demonstrates:

Accident pattern analysis by road condition, weather, and time of day.

Visualization of hotspots by location.

Identification of contributing factors such as vehicle type, alcohol involvement, and police reporting.
