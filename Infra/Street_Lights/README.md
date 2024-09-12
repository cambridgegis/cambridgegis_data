# Street Lights
# INFRA_StreetLights #
## Summary ##
Street Lights within Cambridge from NSTAR Electric

## Description ##
NSTAR Electric previously owned the street lights in Cambridge. This layer reflects the lights through 2005 mapped and maintained by NSTAR Electric. IT IS IMPORTANT TO NOTE THAT THIS LAYER IS GOING THROUGH A COMPLETE REVISION AS PART OF THE CITYWIDE LED PROJECT

## Credits ##
NSTAR Electric

## Use limitations ##
Layer has not been updated after 1995 and not validated by the City of Cambridge.

# INFRA_StreetLights2010Flyover #
## Summary ##
City of Cambridge 1" - 40' base map layers from an April 14, 2010 flyover. Basemap layers created by Infotech America.

## Description ##
City of Cambridge, MA GIS basemap development project encompasses the land area of City of Cambridge with a 200 foot fringe surrounding the area and Charles River shoreline towards Boston. The basemap data was developed at 1" = 40' mapping scale using digital photogrammetric techniques. Planimetric features; both man-made and natural features like vegetation, rivers have been depicted. These features are important to all GIS/mapping applications and publication. A set of data layers such as Buildings, Roads, Rivers, Utility structures, 1 ft interval contours are developed and represented in the geodatabase. The features are labeled and coded in order to represent specific feature class for thematic representation and topology between the features is maintained for an accurate representation at the 1:40 mapping scale for both publication and analysis. The basemap data has been developed using procedures designed to produce data to the National Standard for Spatial Data Accuracy (NSSDA) and is intended for use at 1" = 40 ' mapping scale.THIS ONLY REFLECTS LIGHTS CAPTURED BY THE 2010 FLYOVER AND WAS NOT FIELD VERIFIED

## Credits ##
City of Cambridge GIS, Infotech America
## GIS File Name
INFRA_StreetLights
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>The City of Cambridge owns and maintains most street lights in the City. These were purchased from NSTAR in 2005. Types of lights include Cobrahead (most typical), and various types of </SPAN><SPAN><SPAN>decorative </SPAN></SPAN><SPAN>lighting. Park Lights are in a </SPAN><SPAN><SPAN>separate </SPAN></SPAN><SPAN>layer. Some street lights are owned by other organizations. DCR, the State, and Universities all own lights along the roadways they maintain. These street lights are in a layer 'StreetLightsNonCity'</SPAN></P></DIV></DIV></DIV>

## Purpose
This layer has all City of Cambridge owned street lights. These lights are maintained by the Cambridge Electrical Department.
## Last Modified
08-16-2024
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|PoleID|type: String<br/>width: 15<br/>precision: 0|Unique ID for each street light. This number is also marked on each pole.|
|StreetName|type: String<br/>width: 24<br/>precision: 0|Name of street the light is on|
|StreetSuffix|type: String<br/>width: 4<br/>precision: 0|Street suffix for the street which the light is on.|
|Intersection|type: String<br/>width: 20<br/>precision: 0|Street intersection if the light is at one|
|NumLamps|type: Integer<br/>width: 4<br/>precision: 10|Number of lamps on a pole|
|EditDate|type: String<br/>width: 8<br/>precision: 0|Date (year) lasted edited|
|Description|type: String<br/>width: 25<br/>precision: 0|Type of head on the light. |
|Owner|type: String<br/>width: 25<br/>precision: 0|Owner - always City of Cambridge|
|LEDchk|type: String<br/>width: 6<br/>precision: 0|Field check by Cambridge GIS|
|Neighborhood|type: Double<br/>width: 8<br/>precision: 38|CDD Neighborhood each light is in.|
|Street_ID|type: String<br/>width: 254<br/>precision: 0|Street ID. Each street has a unique ID. The first part of the PoleID.|
|Pole_Num|type: String<br/>width: 254<br/>precision: 0|ID for each pole on a street. Part of the unique PoleID|
|FixtureType|type: String<br/>width: 254<br/>precision: 0|Coding for LED project. Corresponds to the number of LED lights in a fixture. A1 = 120 bulbs, A2 = 80 bulbs, A3 = 40 bulbs per lamp |
|Lamp1|type: String<br/>width: 50<br/>precision: 0|Unique ID for a pole with 2 lamps. |
|Lamp2|type: String<br/>width: 50<br/>precision: 0|Unique ID for a pole with 2 lamps.|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
