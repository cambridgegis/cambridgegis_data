# Solar Installations
## GIS File Name
CDD_SolarInstallations
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This point layer displays the locations of known photovoltaic (PV) and solar hot water installations. The location coordinates may not represent the exact placement of the solar equipment on each parcel, particularly for large parcels or those with solar equipment in multiple locations. This layer only includes PV and solar hot water systems that have been installed. Systems that were previously permitted and installed that have since been retired and removed are not included. This layer will be updated quarterly.</SPAN></P></DIV></DIV></DIV>

## Purpose
To provide information on the number, location and capacity of photovoltaic (PV) and solar hot water installations in Cambridge.
## Last Modified
<<<<<<< HEAD
08-21-2026
=======
05-12-2026
>>>>>>> 44a03d195bb4bc3d9f0bf31452f5ab2d6b2f7be9
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|SystemID|type: String<br/>width: 15<br/>precision: 0|Internal randomly-generated identifier of the system|
|SystemStatus|type: String<br/>width: 15<br/>precision: 0|Status of system installation. Systems that have been installed are considered ‘Active’ systems. Only ‘Active’ systems are included in this layer.|
|SystemType|type: String<br/>width: 30<br/>precision: 0|PV (photovoltaic) or Solar Hot Water|
|FullStreetAddress|type: String<br/>width: 100<br/>precision: 0|Street address|
|BuildingType|type: String<br/>width: 30<br/>precision: 0|Building type for this installation|
|SiteCategory|type: String<br/>width: 30<br/>precision: 0|Site category for this installation|
|KW|type: Double<br/>width: 8<br/>precision: 38|If the record is a photovoltaic (PV) system, the rated capacity of the system in kW. The rated capacity represents the power output potential of the system.|
|SolarHotWaterSystemArea|type: Double<br/>width: 8<br/>precision: 38|If the record is a solar hot water system, the area of the collector in square feet.|
|PermitIssueDate|type: Date<br/>width: 8<br/>precision: 0|Date the solar permit was issued for this installation.|
|created_user|type: String<br/>width: 255<br/>precision: 0||
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_user|type: String<br/>width: 255<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
