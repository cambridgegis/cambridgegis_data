The Cambridge Master Address data is current as of December 2, 2019.

This data is an export from the Cambridge Master address Database.

You can link this file to 3 GIS layers: 

| Field in CSV table	| GIS Layer					| Join field in GIS  
| ------------------	| ---------					| -----------------    
| address_id			| ADDRESS_AddressPoints		| address_id  
| MapLot				| ASSESSING_ParcelsFY2014	| ML  
| BldgID				| BASEMAP_Buildings			| BldgID  

Please note addresses may have duplicate entries if there are more than one 
point of interest, parcel, or building associated with it.

The Points of Interest CSV file can be joined to the ADDRESS_AddressPoints layer to get just the POI names.