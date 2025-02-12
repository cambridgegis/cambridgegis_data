# 2020 Adjusted Blocks
## GIS File Name
DEMOGRAPHICS_AdjustedBlocks2020
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P STYLE="margin:0 0 0 0;"><SPAN>This polygon layer contains the boundaries of the 1044 Census blocks that make up the City of Cambridge for the 2020 Census. Where appropriate, the boundary lines provided by the U.S. Census were adjusted by City staff to match those lines to such features as the City boundary, street centerlines, and parcel lines.</SPAN></P></DIV></DIV></DIV>

## Purpose
Created for spatial analysis of associated 2020 Census demographic data.  Used for planning, mapping, and Community Development Block Grant (CDBG) purposes by the Community Development Department.
## Last Modified
11-25-2024
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|STATEFP20|type: String<br/>width: 2<br/>precision: 0|2020 Census state FIPS code|
|COUNTYFP20|type: String<br/>width: 3<br/>precision: 0|2020 Census county FIPS code|
|TRACTCE20|type: String<br/>width: 6<br/>precision: 0|2020 Census tract code|
|BLOCKCE20|type: String<br/>width: 4<br/>precision: 0|2020 Census tabulation block number|
|GEOID20|type: String<br/>width: 15<br/>precision: 0|Census block identifier; a concatenation of 2020 Census state FIPS code, 2020 Census county FIPS code, 2020 Census tract code, and 2020 Census block number|
|NAME20|type: String<br/>width: 10<br/>precision: 0|2020 Census tabulation block name; a concatenation of ‘Block’ and the tabulation block number|
|MTFCC20|type: String<br/>width: 5<br/>precision: 0|MAF/TIGER Feature Class Code|
|UR20|type: String<br/>width: 1<br/>precision: 0|Reserved for 2020 Census urban/rural indicator (2020 Urban Areas are not yet defined)|
|UACE20|type: String<br/>width: 5<br/>precision: 0|Reserved for 2020 Census urban area code (2020 Urban Areas are not yet defined)|
|UATYPE20|type: String<br/>width: 1<br/>precision: 0|Reserved for 2020 Census urban area type (2020 Urban Areas are not yet defined)|
|FUNCSTAT20|type: String<br/>width: 1<br/>precision: 0|2020 Census functional status|
|ALAND20|type: Double<br/>width: 8<br/>precision: 38| 2020 Census land area (unadjusted - matches raw Census TIGER data)|
|AWATER20|type: Double<br/>width: 8<br/>precision: 38| 2020 Census water area (unadjusted - matches raw Census TIGER data)|
|INTPTLAT20|type: String<br/>width: 11<br/>precision: 0| 2020 Census latitude of the internal point (unadjusted - matches raw Census TIGER data)|
|INTPTLON20|type: String<br/>width: 12<br/>precision: 0| 2020 Census longitude of the internal point (unadjusted - matches raw Census TIGER data)|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
