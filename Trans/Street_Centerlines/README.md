# Street Centerlines
## GIS File Name
TRANS_Centerlines
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This line layer contains centerlines of all paved and unpaved roads, ramps, and bridges in the City of Cambridge. Each centerline segment contains attributes including street name, street type, address ranges, and one-way designations.</SPAN></P></DIV></DIV></DIV>

## Purpose
This layer was created for addressing, routing applications, base maps, and general mapping purposes, both for internal and external use.
## Last Modified
12-12-2024
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|ID|type: String<br/>width: 40<br/>precision: 0|Unique identifier for each street segment|
|ROADWAYS|type: String<br/>width: 1<br/>precision: 0|Divided street designation<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>T</td><td>Divided</td></tr><tr><td>F</td><td>Not divided</td></tr></table>|
|Street|type: String<br/>width: 40<br/>precision: 0|Full street name with street type|
|Street_Name|type: String<br/>width: 30<br/>precision: 0|Street name only|
|Street_Type|type: String<br/>width: 10<br/>precision: 0|Street type|
|Street_ID|type: Double<br/>width: 8<br/>precision: 38|Street ID number from master address database|
|Alias|type: String<br/>width: 50<br/>precision: 0|Alternate street name|
|L_From|type: Integer<br/>width: 4<br/>precision: 10|Left side address range 'from'|
|L_To|type: Integer<br/>width: 4<br/>precision: 10|Left side address range 'to'|
|R_From|type: Integer<br/>width: 4<br/>precision: 10|Right side address range 'from'|
|R_To|type: Integer<br/>width: 4<br/>precision: 10|Right side address range 'to|
|FromNode|type: Double<br/>width: 8<br/>precision: 38|New 'from node' number|
|ToNode|type: Double<br/>width: 8<br/>precision: 38|New 'to node' number|
|Direction|type: String<br/>width: 5<br/>precision: 0|One-way designation<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>0</td><td>Two-way street segment</td></tr><tr><td>1</td><td>One-way street in same direction as street segment</td></tr><tr><td>-1</td><td>One-way street in opposite direction of street segment</td></tr></table>|
|Restriction|type: String<br/>width: 1<br/>precision: 0|Truck restriction designation|
|Label|type: String<br/>width: 50<br/>precision: 0|Street name field for labels when mapping|
|MajorRoad|type: SmallInteger<br/>width: 2<br/>precision: 5|Major road designation|
|ZIP_Left|type: String<br/>width: 8<br/>precision: 0|Left side zip code|
|ZIP_Right|type: String<br/>width: 8<br/>precision: 0|Right side zip code|
|EditDate|type: String<br/>width: 4<br/>precision: 0|Date of last edit|
|Potential_L_From|type: Integer<br/>width: 4<br/>precision: 10|Potential left side address range 'from'|
|Potential_L_To|type: Integer<br/>width: 4<br/>precision: 10|Potential left side address range 'to'|
|Potential_R_From|type: Integer<br/>width: 4<br/>precision: 10|Potential right side address range 'from'|
|Potential_R_To|type: Integer<br/>width: 4<br/>precision: 10|Potential right side address range 'to'|
|Potentail_Range_Done|type: SmallInteger<br/>width: 2<br/>precision: 5|Potential range researched and populated|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
