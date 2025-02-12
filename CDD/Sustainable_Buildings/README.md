# Sustainable Buildings
## GIS File Name
CDD_SustainableBuildings
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P STYLE="margin:0 0 0 0;"><SPAN><SPAN>This point layer shows the location of sustainable buildings in Cambridge. For inclusion in this layer, a building must do at least one of the following: qualify for the City’s Article 22 regulatory process; be certified by Passive House; be certified by Enterprise Green Communities; or be certified by LEED</SPAN></SPAN><SPAN /><SPAN /><SPAN><SPAN>under a LEED version that requires the whole building to meet sustainability standards. Some buildings meet two or more of these criteria. Additionally, this layer contains information about other certifications (Energy Star, Fitwel, and WELL) that may apply to the included buildings. If an included building participates in the City’s BEUDO regulatory process, this layer provides two key emissions figures for the building. Information provided about the applicable sustainable building programs for qualifying buildings includes certification levels, certification types, ratings, or scores. This layer includes data from City and non-City sources.</SPAN></SPAN></P></DIV></DIV></DIV>

## Purpose
This layer was created for general use by CDD staff.  It combines information from eight sustainable building certification programs, including two City regulatory programs, to show the extent and location of sustainable buildings in Cambridge.
## Last Modified
09-05-2024
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|BldgID|type: String<br/>width: 50<br/>precision: 0|Unique ID for database from GIS.|
|Latitude|type: Double<br/>width: 8<br/>precision: 38|Geographic coordinate from GIS Bldg ID centroid file.|
|Longitude|type: Double<br/>width: 8<br/>precision: 38|Geographic coordinate from GIS Bldg ID centroid file.|
|Article22_SystemLevelEquivalenc|type: String<br/>width: 150<br/>precision: 0||
|Article22|type: String<br/>width: 3<br/>precision: 0|"Yes" indicates Article 22 building.|
|BEUDO|type: String<br/>width: 3<br/>precision: 0|"Yes" indicates BUEDO building.|
|EnergyStar|type: String<br/>width: 3<br/>precision: 0|"Yes" indicates EnergyStar building.|
|EnergyStar_CountYearsCert|type: SmallInteger<br/>width: 2<br/>precision: 5|Number of  years certified. EnergyStar certification may be renewed annually.|
|EnergyStar_LastYearCert|type: String<br/>width: 4<br/>precision: 0|Year of last certification.|
|EnergyStar_LastCertScore|type: SmallInteger<br/>width: 2<br/>precision: 5|Most recent EnergyStar score.|
|EnterpriseGC|type: String<br/>width: 3<br/>precision: 0|"Yes" indicates Enterprise Green Communities building.|
|EnterpriseGC_CertTemplate|type: String<br/>width: 100<br/>precision: 0|Certification version.|
|EnterpriseGC_PointsAchieved|type: SmallInteger<br/>width: 2<br/>precision: 5|Enterprise Green Communities score.|
|Fitwel|type: String<br/>width: 3<br/>precision: 0|"Yes" indicates Fitwel building.|
|Fitwel_StarRating|type: SmallInteger<br/>width: 2<br/>precision: 5|Numerical Fitwel rating.|
|LEED|type: String<br/>width: 3<br/>precision: 0|"Yes" indicates LEED building.|
|LEED_TotalCerts|type: SmallInteger<br/>width: 2<br/>precision: 5|Number of certifications applying to the whole building.  The LEED fields contain details about  certifications that are "whole-building," not referring to one part of the building only or or to building operations.|
|LEED_LastCertDate|type: Date<br/>width: 8<br/>precision: 0|Date of last certification applying to the whole building.|
|LEED_LastSystemVersion|type: String<br/>width: 100<br/>precision: 0|Certification version and rating system.|
|LEED_LastCertLevel|type: String<br/>width: 50<br/>precision: 0|LEED certifictation level at which whole building is certified. Certified/Silver/Gold/Platinum: Does not not include "registered" buildings.|
|PassiveHouse|type: String<br/>width: 3<br/>precision: 0|"Yes" indicates Passive House building.|
|PassiveHouse_CertVersion|type: String<br/>width: 100<br/>precision: 0|Certification version.|
|WELL|type: String<br/>width: 3<br/>precision: 0|"Yes" indicates WELL building.|
|WELL_Version|type: String<br/>width: 50<br/>precision: 0|Certification version.|
|WELL_ProjectType|type: String<br/>width: 150<br/>precision: 0|WELL project type.|
|WELL_CertLevel|type: String<br/>width: 50<br/>precision: 0|Certification level. Certified Pilot/Compliance/Bronze/Silver/Gold/Platinum or Health-Safety Rated: Does not include "registered" or "precertified" buildings.|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
