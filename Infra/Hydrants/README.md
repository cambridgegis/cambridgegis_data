# Hydrants
## GIS File Name
INFRA_Hydrants
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>Fire Hydrants are maintained by the Engineering group at the Cambridge Water Department, Hydrants are also monitored by Cambridge Fire Department. Used for public safety, mapping, and water distribution.</SPAN></P></DIV></DIV></DIV>

## Purpose
Fire Hydrants within the City of Cambridge
## Last Modified
02-03-2025
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|ANCILLARYROLE|type: SmallInteger<br/>width: 2<br/>precision: 5|Ancillary role for hydrant.<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>0</td><td>None</td></tr><tr><td>1</td><td>Source</td></tr><tr><td>2</td><td>Sink</td></tr></table>|
|ENABLED|type: SmallInteger<br/>width: 2<br/>precision: 5|Enabled?<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>0</td><td>False</td></tr><tr><td>1</td><td>True</td></tr></table>|
|INSTALLDATE|type: Date<br/>width: 8<br/>precision: 0|Installation date.|
|ROTATION|type: Double<br/>width: 8<br/>precision: 38|Annotation rotation value.|
|LIFECYCLESTATUS|type: String<br/>width: 20<br/>precision: 0|Lifecycle status.<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>ACT</td><td>Active</td></tr><tr><td>ABN</td><td>Abandoned</td></tr><tr><td>PROP</td><td>Proposed</td></tr><tr><td>MITFL</td><td>MIT Fire Loop</td></tr></table>|
|SUBTYPE|type: Integer<br/>width: 4<br/>precision: 10|Subtype.<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>1</td><td>GateHydrant</td></tr><tr><td>2</td><td>NonGateHydrant</td></tr></table>|
|LASTEDITOR|type: String<br/>width: 20<br/>precision: 0|Last editor.|
|LASTEDITDATE|type: Date<br/>width: 8<br/>precision: 0|Last edit date.|
|LASTSOURCE|type: String<br/>width: 20<br/>precision: 0|Last edit source.|
|HYDRANT_ID|type: String<br/>width: 30<br/>precision: 0|Unique hydrant ID.|
|GATE|type: SmallInteger<br/>width: 2<br/>precision: 5|Gate?<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>0</td><td>False</td></tr><tr><td>1</td><td>True</td></tr></table>|
|CONTRACTAUTHORITY|type: String<br/>width: 50<br/>precision: 0|Contract authority<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>MWRA</td><td>MWRA</td></tr><tr><td>CAM</td><td>City</td></tr><tr><td>PRI</td><td>Private</td></tr><tr><td>HVDU</td><td>Harvard</td></tr><tr><td>MIT</td><td>MIT</td></tr><tr><td>UNK</td><td>Unknown</td></tr></table>|
|HYDRANT_GPM|type: Double<br/>width: 8<br/>precision: 8|Gallons per minute.|
|Notes|type: String<br/>width: 255<br/>precision: 0|Notes.|
|HYDRANT_LOCATION|type: String<br/>width: 100<br/>precision: 0||
|HYDRANT_MANF|type: String<br/>width: 50<br/>precision: 0||
|HYDRANT_COLOR|type: String<br/>width: 25<br/>precision: 0||
|HYDRANT_OWNER|type: String<br/>width: 50<br/>precision: 0||
|SWEEPER_HYDRANT|type: String<br/>width: 1<br/>precision: 0||
|HYDRANT_DRAIN|type: String<br/>width: 20<br/>precision: 0||
|LAST_DATE_TESTED|type: Date<br/>width: 8<br/>precision: 0||
|COMMENTS|type: String<br/>width: 255<br/>precision: 0||
|created_user|type: String<br/>width: 255<br/>precision: 0||
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_user|type: String<br/>width: 255<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
