# Coursera_Capstone_1

## CRISP DM 

___Business Understanding___

The Seattle government is going to prevent avoidable car accidents by employing methods that alert drivers, health system, and police to remind them to be more careful in critical situations.
In most cases, not paying enough attention during driving, abusing drugs and alcohol or driving at very high speed are the main causes of occurring accidents that can be prevented by enacting harsher regulations. Besides the aforementioned reasons, weather, visibility, or road conditions are the major uncontrollable factors that can be prevented by revealing hidden patterns in the data and announcing warning to the local government, police and drivers on the targeted roads.
The target audience of the project is local Seattle government, police, rescue groups, and last but not least, car insurance institutes. The model and its results are going to provide some advice for the target audience to make insightful decisions for reducing the number of accidents and injuries for the city.

__DATA___

A comprehensive dataset of 226,000 accidents occurring between 2004–2019 in the Seattle city area was obtained from the Seattle Open Data Portal. The  221,389 row dataset has 40 columns describing the details of each accident including the weather conditions, collision type, date/time of accident and location (latitude and longitude).
I will use a Choropleth map (created using the Python Folium package) to reveal which accidents occur more frequently in specific areas of the city, 

One of the 40 columns in the dataset encodes the Seattle Department of Transport (SDOT) accident severity metric, according to the following schema:
0: Unknown/no data
1: Property damage only
2: Minor injury collision
2b: Major injury collision
3: Fatality collision

I will use the severity codes assigned to each accident, to identify the neighbourhoods with the highest mean accident severity codes.

Finally I will use the  timestamp data in order to  search for temporal variations in the rate of road accidents in Seattle. 

___DATA Preprocessing__ 

See next weeks assingment 
