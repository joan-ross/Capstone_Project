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