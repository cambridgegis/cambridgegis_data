# EVSE
## GIS File Name
CDD_EVSE
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P STYLE="margin:0 0 11 0;"><SPAN><SPAN>Created for the Environmental Transportation &amp; Planning Division to visualize and analyze the accessibility and capacity of EV charging supply in Cambridge.</SPAN></SPAN></P></DIV></DIV></DIV>

## Purpose
This point layer contains the locations of electric vehicle supply equipment (EVSE) within Cambridge. Electrical permit data verifies where electrical capacity has been approved, not that it was installed, nor that an EVSE was attached it, or if it was uninstalled later. Public stations may exist that are not connected to any of the major network providers, and there may also be stations that are incapable of joining to a network.
## Last Modified
03-14-2023
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|full_address|type: String<br/>width: 255<br/>precision: 0|Full Street Address|
|bldg_ID|type: String<br/>width: 255<br/>precision: 0|GIS Building ID|
|install_date|type: String<br/>width: 255<br/>precision: 0|Date of EVSE installation. Installation Date. This is difficult to determine. Rely on a variety of sources and must perform research to populate|
|structure|type: String<br/>width: 255<br/>precision: 0|Use type of the parking spot|
|site_description|type: String<br/>width: 255<br/>precision: 0|Additional site information|
|owntype|type: String<br/>width: 255<br/>precision: 0|Parking/EVSE ownership|
|access|type: String<br/>width: 255<br/>precision: 0|Information on who can utilize the EVSE|
|fee|type: String<br/>width: 255<br/>precision: 0|Is there a fee|
|fee_hour|type: Double<br/>width: 8<br/>precision: 38|Dollar per hour fee for using EVSE|
|fee_kWh|type: String<br/>width: 255<br/>precision: 0|Dollar per kWh fee for using EVSE|
|limits_penalties|type: String<br/>width: 255<br/>precision: 0|Known limitations and associated fees|
|Stations|type: Double<br/>width: 8<br/>precision: 38|Number of stations at location|
|lvl1_ports|type: Double<br/>width: 8<br/>precision: 38|Number of level 1 ports |
|lvl2_ports|type: Double<br/>width: 8<br/>precision: 38|Number of level 2 ports |
|lvl3_ports|type: Double<br/>width: 8<br/>precision: 38|Number of level 3 ports |
|dedicated_spaces|type: Double<br/>width: 8<br/>precision: 38|Total spaces reserved for EVs|
|EVSEtype_1|type: String<br/>width: 255<br/>precision: 0||
|num_type_1|type: Double<br/>width: 8<br/>precision: 38||
|EVSEtype_2|type: String<br/>width: 255<br/>precision: 0||
|num_type_2|type: Double<br/>width: 8<br/>precision: 38||
|EVcapacity|type: Double<br/>width: 8<br/>precision: 38|Total EV charging ports|
|notes|type: String<br/>width: 255<br/>precision: 0|Miscellaneous notes related to station|
|created_user|type: String<br/>width: 255<br/>precision: 0|Auto generate and auto populated using editor tracking|
|created_date|type: Date<br/>width: 8<br/>precision: 0|Auto generate and auto populated using editor tracking|
|last_edited_user|type: String<br/>width: 255<br/>precision: 0|Auto generate and auto populated using editor tracking|
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0|Auto generate and auto populated using editor tracking|
