# Wards and Sub-Precincts
## GIS File Name
ELECTIONS_WardsSubPrecincts
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This polygon layer contains 11 wards, 33 precincts, and 9 sub-precincts within the City of Cambridge. These were adjusted in 2021 from the 2020 U.S. Census.</SPAN></P><P><SPAN>The Massachusetts Legislative boundaries do not follow the Cambridge Ward and Precinct boundaries in several areas. In part, this was because of the compressed timeline due to the Covid-19 pandemic during the 2020 US Census. Municipalities and the State were unable to coordinate local and legislative districts, and as a result sub-precincts within 9 precincts were unavoidable. There are 9 precincts that are subdivided for all but local elections. </SPAN><SPAN><SPAN>Voters in a sub-precinct are listed on a separate voting list and have different ballots from other voters in the precinct during State Elections.</SPAN></SPAN></P><P><SPAN>This layer contains the subdivided precincts. Please see the ELECTIONS_WardsPrecincts layer for the undivided precincts.</SPAN></P></DIV></DIV></DIV>

## Purpose
This layer was created for general use by the Cambridge Election Commission and for public distribution. Cambridge wards and precincts which designate where voters will vote.

## Last Modified
06-06-2022
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|WardPrecinctSubPrecinct|type: String<br/>width: 10<br/>precision: 0|Ward and Precinct, with Sub-Precinct where applicable|
|Sort|type: SmallInteger<br/>width: 2<br/>precision: 5|For sorting by Ward, Precinct, and Sub-Precinct where applicable|
|PrecinctSubPrecinct|type: String<br/>width: 5<br/>precision: 0|Precinct, with Sub-Precinct where applicable|
|TOTALPOP|type: Double<br/>width: 8<br/>precision: 38|Total population of covered area from 2020 US Census
|
|Ward|type: String<br/>width: 4<br/>precision: 0|Ward|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
