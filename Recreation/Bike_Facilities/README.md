# Bike Facilities
## GIS File Name
RECREATION_BikeFacilities
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This line layer indicates streets within the City of Cambridge that have pavement markings or construction features that facilitate bicycle use. It also contains multi-purpose paths where bicycles can be used off the street.</SPAN></P></DIV></DIV></DIV>

## Purpose
Created for planning purposes, map making, and for public distribution.
## Last Modified
08-11-2025
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|Street|type: String<br/>width: 40<br/>precision: 0|Same as "STREET" field from RoadCenterline layer, or name of mutli-use path entered manually|
|ExistingFacility|type: Double<br/>width: 8<br/>precision: 38|3- or 4-digit code that corresponds to a bicycle facility type for existing facilities.  Value is NULL if the segment is a PlannedFacility|
|PlannedFacility|type: Double<br/>width: 8<br/>precision: 38|4- or 5-digit code beginning with "9" that corresponds to a bicycle facility type for planned facilities.  Value is NULL if the segment is an ExistingFacility|
|FacilityType|type: String<br/>width: 255<br/>precision: 0|The type of bicycle facility by category|
|FacilityDetails|type: String<br/>width: 255<br/>precision: 0|Further details about the bicycle facility type on this segment, such as direction of travel, number of lanes, whether street is one-way or two-way street|
|LaneMultiplier|type: Double<br/>width: 8<br/>precision: 38|The number of travel lanes along the bicycle facility line segment (1 or 2) to be used as a multiplier to arrive at a number for lane length|
|LaneLengthFeet|type: Double<br/>width: 8<br/>precision: 38|Length in feet of all lanes of travel along the segment of the bicycle facility.  Calculated by multiplying  Shape_Length by LaneMultiplier|
|YearAdded|type: Double<br/>width: 8<br/>precision: 38|The year the facility was built|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
