# 2020 Adjusted Tracts
## GIS File Name
DEMOGRAPHICS_AdjustedTracts2020
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P STYLE="margin:0 0 0 0;"><SPAN>This polygon layer contains the boundaries of the 33 Census tracts that make up the City of Cambridge for the 2020 Census. Where appropriate, the boundary lines provided by the U.S. Census were adjusted by City staff to match those lines to such features as the City boundary, street centerlines, and parcel lines.</SPAN></P></DIV></DIV></DIV>

## Purpose
Created for spatial analysis of associated 2020 Census demographic data.  Used for planning, mapping, and Community Development Block Grant (CDBG) purposes by the Community Development Department.
## Last Modified
10-21-2021
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|STATEFP20|type: String<br/>width: 2<br/>precision: 0|2020 Census state FIPS code|
|COUNTYFP20|type: String<br/>width: 3<br/>precision: 0|2020 Census county FIPS code|
|TRACTCE20|type: String<br/>width: 6<br/>precision: 0|2020 Census tract code|
|GEOID20|type: String<br/>width: 12<br/>precision: 0|Census tract identifier; a concatenation of Current state FIPS code, county FIPS code, and census tract code
|
|NAME20|type: String<br/>width: 7<br/>precision: 0|2020 Census tract name, this is the census tract code converted to an integer or integer with 2-decimals if the last two characters of the code are not both zeros.|
|NAMELSAD20|type: String<br/>width: 13<br/>precision: 0|2020 translated legal/statistical area description and the census tract name|
|MTFCC20|type: String<br/>width: 5<br/>precision: 0|MAF/TIGER Feature Class Code|
|FUNCSTAT20|type: String<br/>width: 1<br/>precision: 0|2020 functional status|
|ALAND20|type: Double<br/>width: 8<br/>precision: 38|2020 land area (unadjusted - matches raw Census TIGER data)|
|AWATER20|type: Double<br/>width: 8<br/>precision: 38|2020 water area (unadjusted - matches raw Census TIGER data)|
|INTPTLAT20|type: String<br/>width: 11<br/>precision: 0|2020 latitude of the internal point (unadjusted - matches raw Census TIGER data)
|
|INTPTLON20|type: String<br/>width: 12<br/>precision: 0|2020 longitude of the internal point (unadjusted - matches raw Census TIGER data)|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
