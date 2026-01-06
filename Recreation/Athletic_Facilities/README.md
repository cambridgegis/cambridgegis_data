# Athletic Facilities
## GIS File Name
RECREATION_AthleticFacilities
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This point layer contains the outdoor public athletic facilities within Cambridge. Athletic facilities are located within city parks in in city playgrounds. </SPAN></P></DIV></DIV></DIV>

## Purpose
Created for general use within the Community Development Department (CDD) and for map making.
## Last Modified
01-05-2026
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|JOIN_ID|type: Double<br/>width: 8<br/>precision: 38|Internal ID|
|FCODE|type: Integer<br/>width: 4<br/>precision: 10|Open space classification|
|NAME|type: String<br/>width: 75<br/>precision: 0|Name of feature|
|Athletics|type: String<br/>width: 50<br/>precision: 0|Type of faciility. See UseCode below for full list.|
|UseCode|type: Double<br/>width: 8<br/>precision: 38|Numerical reference to Athletics type.<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>1</td><td>Baseball (Little League)</td></tr><tr><td>2</td><td>Baseball (High School)</td></tr><tr><td>3</td><td>Basketball</td></tr><tr><td>4</td><td>Soccer</td></tr><tr><td>5</td><td>Softball</td></tr><tr><td>6</td><td>Tennis</td></tr><tr><td>7</td><td>Street Hockey</td></tr><tr><td>8</td><td>Track and Field</td></tr><tr><td>9</td><td>Swimming (Outdoor)</td></tr><tr><td>10</td><td>Football</td></tr><tr><td>11</td><td>Golf</td></tr><tr><td>12</td><td>Ice Skating (Indoor)</td></tr><tr><td>13</td><td>Table Tennis</td></tr></table>|
|UseID|type: String<br/>width: 10<br/>precision: 0|Combination of JOIN_ID and UseCode to give a numerical reference to the park name and facility type for each facility.|
|created_user|type: String<br/>width: 255<br/>precision: 0||
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_user|type: String<br/>width: 255<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
