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
point of interest, parcel, or building associated with it.