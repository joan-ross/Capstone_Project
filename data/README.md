# Data Dictionary

All 2018 Bloomington sidewalk data from [Data.gov] ()

This is a dictionary of the datasets used in my project.

## Pavement Distress Report

| field | type | description |
| ----- | ----------- | -------------- |
Branch ID| object| Name of the branch the report is located in.|
Name| object| Name of the street the report is located in.|
Section ID| object| identification number for the section the report is located in.|
System ID| object| identification number of the report in the system.|
From| object| address of the starting point of the problem area.|
To| object| address of the ending point of the problem area.|
True Area (Ft2)| int64| area of the damage in feet squared.|
Length (Ft)| float64| how long the damage area is in feet.|
PCI| int64| Pavement Condition Index. How bad the pavement is on a scale of 1-100.|
Sample Number| int64| identification number of pavement sample taken.|
Distress Description| object| type of damage done to pavement.|
Quantity| float64| Unable to find what quantity refers to exactly.|
Quantity Units| object| the measurement units of the quantity.|
Severity| object| letter that classifies how bad the damage is.|

This table is a report that shows how they go about classifying and organizing pavement that needs work. It gives identifiers like the location and street name, how big of an area it covers, and what type of damage and how bad it is. This allows the users to keep track of what work needs to be done and where easier. 

## Sidewalk Condition Report

| field | type | description |
| ----- | ----------- | -------------- |
OBJECTID| int64| ID number to classify the sidewalk report.|
ASSETID| object| ID number to classify the asset of the sidewalk.|
CONDITION| object| tells the condition the sidewalk is in.|
TYPE| object| tells what kind of sidewalk it is in a material sense.|
Roadname| object| name of the road the sidewalk is located on.|
SECTIONID| object| identification number of the sidewalk report in the system.|
Length (ft)| float64| length of sidewalk in feet.|
Length (mi)| float64| length of sidewalk in miles.|
BACKIMAGE| object| link to image presumably of the sidewalk (error message when opened).| 
VIEWER| object| link to place to view the sidewalk (error message when opened).|
IntVIEWER| object|link to place to view the sidewalk (error message when opened).|

This table is a report of specifically sidewalks in need of repair. It also has identifiers such as a specific ID number and location of the damaged sidewalk to tell where it is. It also classifies which sidewalks are in need of repair the most and how long the sidewalks are. It's purpose is to make it easier for the user to keep track of which sidewalks are in need of repair.

Data and tables like this a relevant because they help with the upkeep of cities, ensuring that they remain walkable and accessible to the residents and people who visit the city.

For view and explanation of cleaned data process visit `src\Clean_Data_Explanation.ipynb`
For view and explanation of the raw data visit `src\Raw_Data_Explanation.ipynb`