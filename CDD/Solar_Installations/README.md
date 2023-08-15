# Solar Installations
## GIS File Name
CDD_SolarInstallations
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P STYLE="margin:0 0 0 0;"><SPAN><SPAN>This point layer identifies parcels with known solar installations. It includes both photovoltaic (PV) and solar hot water installations. The point may not fall in the exact location of the solar equipment, especially on larger parcels, or parcels with equipment in multiple locations. This dataset will be updated regularly with new installations.</SPAN></SPAN></P><P /></DIV></DIV></DIV>

## Purpose
To provide information on the quantity, location, and capacity of solar PV and hot water installations in Cambridge.
## Last Modified
12-05-2022
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|SystemID|type: String<br/>width: 15<br/>precision: 0|Internal randomly-generated identifier of the system|
|SystemStatus|type: String<br/>width: 15<br/>precision: 0|Status of system (active, retired, etc.)|
|SystemType|type: String<br/>width: 30<br/>precision: 0|PV (photovoltaic) or Solar Hot Water|
|FullStreetAddress|type: String<br/>width: 100<br/>precision: 0|Street address|
|BuildingType|type: String<br/>width: 30<br/>precision: 0|Building type for this installation|
|SiteCategory|type: String<br/>width: 30<br/>precision: 0|Site category for this installation|
|KW|type: Double<br/>width: 8<br/>precision: 38|If the record is a PV system, the rated capacity of the system in KW.|
|SolarHotWaterSystemArea|type: Double<br/>width: 8<br/>precision: 38|If the record is a solar hot water system, the area of the collector in square feet.|
|PermitIssueDate|type: Date<br/>width: 8<br/>precision: 0|Date the solar permit was issued for this installation.|
|created_user|type: String<br/>width: 255<br/>precision: 0||
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_user|type: String<br/>width: 255<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
