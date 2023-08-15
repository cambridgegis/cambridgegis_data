# FY2013 Parcels
# Tax Tables #

The TaxFY13 CAMA data is current as of Jan. 01, 2012.
 
Link the field ML in the corresponding ASSESSING_ParcelsFY20xx.geojson file to field ML in the CSV file. 

| Field							| Description |  
| -----							| ----------- |  
| ML							| Assessor Map & Lot |  
| Location						| Assessors address on deed |  
| LandArea						| Parcel area in feet |  
| UseCode						| State Land Use Code |  
| UseDescription				| State Land Use Description |  
| TotalAppraisedLandValue		| Land value only |  
| TotalAppraisedImprovements	| Building value only |  
| TotalAppraisedParcelValue		| Both land and building value |  
| BookPage						| Southern Middlesex Registry of Deeds book and page number |  
| SaleDate						| Date of last sale |  
| StyleDesc						| Building style (exterior) |  
| LivingArea					| Building living area (interior) |  
| Occupancy						| Number of Units |  
| AYBYrBuilt					| Year building constructed |  
| BldgStories					| Number of stories |  


Questions? CambridgeGIS@cambridgema.gov## GIS File Name
ASSESSING_ParcelsFY2013
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This polygon layer contains all of the property parcels in Cambridge. Each parcel has a unique Map and Lot ID number that links it to a record in the Assessing Department's Vision database system. </SPAN><SPAN><SPAN>This data is updated through January 1, 2012.</SPAN></SPAN></P></DIV></DIV></DIV>

## Purpose
Created for internal use by the Assessing Department to provide a visual reference associated with each parcel in the CAMA database. Created for interdepartmental and external use as part of the web viewers on the City's website. Also created for addressing/geocoding needs, although the Buildings and Master Address List are currently more accurate than Parcels. 

NOTE: The Parcels GIS data layer is NOT used by Assessing to calculate land area or taxes. Assessors refer to actual deeds or plans accepted by the Massachusetts Land Court. The figures stored in the GIS data layer are for general reference purposes only.
## Last Modified
09-12-2017
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|ML|type: String<br/>width: 16<br/>precision: 0|Map and Lot numbers separated by "-"|
|MAP|type: String<br/>width: 5<br/>precision: 0|Map (block) number|
|LOT|type: String<br/>width: 5<br/>precision: 0|Lot (parcel) number|
|FCODE|type: Integer<br/>width: 4<br/>precision: 10|Parcel type code|
|UYEAR|type: Integer<br/>width: 4<br/>precision: 10|Update year|
|Approved|type: String<br/>width: 35<br/>precision: 0|Assessing staff who approved most recent edit|
|Editor|type: String<br/>width: 20<br/>precision: 0|Initials of person making most recent edit|
|EditDate|type: Date<br/>width: 8<br/>precision: 0|Date of most recent edit|
