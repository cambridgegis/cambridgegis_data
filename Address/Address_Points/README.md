# Address Points
The Cambridge Master Address data is updated whenever the *ADDRESS_AddressPoints.geojson* file is updated.

This data is an export from the Cambridge Master Address Database, enhanced with information from various GIS polygon layers maintained by Cambridge GIS and also available on the city's Open Data Portal: [Master Address List](https://data.cambridgema.gov/Geographic-Information-GIS-/Master-Addresses-List/vup6-kpwv).

You can link this file to 3 GIS layers: 

| Field in CSV table	| GIS Layer					| Join field in GIS  
| ------------------	| ---------					| -----------------    
| address_id			| ADDRESS_AddressPoints		| address_id  
| ml    				| ASSESSING_ParcelsFY2xxx	| ML  
| BldgID				| BASEMAP_Buildings			| BldgID  

The Points of Interest CSV file can be joined to the ADDRESS_AddressPoints layer to get just the POI names.

Please note addresses may have duplicate entries if there are more than one 
point of interest, parcel, or building associated with it.## GIS File Name
ADDRESS_AddressPoints
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This project was done in-house as part of the Master Address Project. Thorough field checks have been carried out to ensure accuracy. Crosschecks have been made with various departments, including Assessing, Community Development, Elections, Emergency Communications, Inspectional Services, and Public Works. Each address point has attribute information including addresses, unique tax parcel ID and building ID which is useful for many different city departments for their respective systems and tools. Aside from housing and business addresses the following have also been included in this layer: Empty lots for potential addresses; Parks and open space addresses; Call box locations.</SPAN></P></DIV></DIV></DIV>

## Purpose
This point layer includes all address points in the City of Cambridge. These are mapped to the doorway location of the building whenever possible
## Last Modified
07-07-2025
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|BldgID|type: String<br/>width: 8<br/>precision: 0|Unique building ID|
|ml|type: String<br/>width: 10<br/>precision: 0|Parcel ID (map-lot)|
|Entry|type: String<br/>width: 20<br/>precision: 0|Main point of entry|
|EditDate|type: String<br/>width: 8<br/>precision: 0|Date of last GIS edit|
|TYPE|type: String<br/>width: 20<br/>precision: 0|Type of address (building, park, other)|
|StNm|type: String<br/>width: 15<br/>precision: 0|Street Number|
|StName|type: String<br/>width: 50<br/>precision: 0|Street Name|
|address_id|type: Double<br/>width: 8<br/>precision: 19|Unique address ID|
|Full_Addr|type: String<br/>width: 50<br/>precision: 0|Full street number and address|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
