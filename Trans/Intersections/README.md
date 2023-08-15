# Intersections
## GIS File Name
TRANS_Intersections
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This point layer contains start and end nodes for all of the street segments in Cambridge. It also contains street names for all intersections.</SPAN></P></DIV></DIV></DIV>

## Purpose
Created in accompaniment with the Centerlines data layer. Each street segment has a "from node" and a "to node" to connect the streets and to indicate the direction of the segment.
## Last Modified
09-29-2022
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|NodeNumber|type: Double<br/>width: 8<br/>precision: 38|Node ID - relates to "FromNode" and "ToNode" of each street segment|
|Intersection|type: String<br/>width: 75<br/>precision: 0|Intersecting street names separated by "&"|
|IntersectingStreetCount|type: Integer<br/>width: 4<br/>precision: 10|Number of intersecting streets at the node|
|TurnRestriction|type: String<br/>width: 10<br/>precision: 0|Vehicle turning restrictions at intersection|
|P_X|type: Double<br/>width: 8<br/>precision: 38|X coordinate of point|
|P_Y|type: Double<br/>width: 8<br/>precision: 38|Y coordinate of point|
|Street1|type: String<br/>width: 30<br/>precision: 0|Unpopulated|
|EditDate|type: String<br/>width: 4<br/>precision: 0||
|Street2|type: String<br/>width: 30<br/>precision: 0|Unpopulated|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
