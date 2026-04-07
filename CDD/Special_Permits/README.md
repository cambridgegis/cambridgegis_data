# Special Permits
## GIS File Name
CDD_SpecialPermits
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This point layer includes the location, identifying details, and status of three types of cases that come before the Planning Board: Special Permit projects (PB), Affordable Housing Overlay Design Review cases (AHO), and Planning Board Advisory Consultation cases (PBAC). Project or case status includes Permitting/Reviewing, Permitted/Reviewed, Under construction, and Built. This information is maintained and updated by the Zoning &amp; Development Division of the Community Development Department.</SPAN></P></DIV></DIV></DIV>

## Purpose
Points showing the locations of cases that come before the Planning Board, including Special Permit projects, Affordable Housing Overlay Design Review cases, and Planning Board Advisory Consultation cases.
## Last Modified
04-07-2026
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|CaseID|type: String<br/>width: 50<br/>precision: 0|Unique ID for Special Permit applications, with letter prefix indicating case type: PB- (Planning Board Special Permit), AHO- (Affordable Housing Overlay Design Review), and PBAC- (Planning Board Advisory Consultation).  Numbers will have three digits, starting with 00 for numbers under 10, and starting with 0 for numbers under 100.|
|CaseType|type: String<br/>width: 100<br/>precision: 0|Full name/description of case type indicated by CaseID prefix: Planning Board Special Permit; Affordable Housing Overlay Design Review; Planning Board Advisory Consultation|
|ProjectName|type: String<br/>width: 50<br/>precision: 0|Name by which the project is known; can be the address if no other moniker is in use|
|ProjectAddress|type: String<br/>width: 50<br/>precision: 0|Address of the project|
|MapLots|type: String<br/>width: 100<br/>precision: 0|Map-Lot numbers of affected parcels.  Can be more than one.|
|CaseStatus|type: String<br/>width: 30<br/>precision: 0|Status of the special permit application and project.  Mapped values are Permitting, Reviewing (for AHO), Permitted, Reviewed (for AHO), Under construction, and Built.  Other values (not mapped) include Denied, Expired, No decision, Superseded, and Withdrawn.|
|AHOWebLink|type: String<br/>width: 255<br/>precision: 0|URL for a separate AHO project page that is not on the special permits web page|
|ShowOnWeb|type: SmallInteger<br/>width: 2<br/>precision: 5|Yes/No for whether to display a point for the project on the Special Permits web map. For older projects with Status = Built, having  ShowOnWeb = No identifies them as belonging to  separate layer on the web map that can be toggled on and off.|
|ShowMoreInfoOnWeb|type: SmallInteger<br/>width: 2<br/>precision: 5|Yes/No for whether to include a link to the project page in the callout box on the web map. Where ShowMoreInfoLinek= No, then ShowOnWeb = No also.  Where  ShowMoreInfoLink = Yes, there are some older built projects and others that are never shown on the map have ShowOnWEb = No. This would apply to Planning Board Special Permit cases only, not AHO Design Review or PBAC .|
|Longitude|type: Double<br/>width: 8<br/>precision: 38|X coordinate of point per GIS|
|Latitude|type: Double<br/>width: 8<br/>precision: 38|X coordinate of point per GIS|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
