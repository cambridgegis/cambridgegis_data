# Special Permit Areas
## GIS File Name
CDD_SpecialPermitAreas
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This polygon layer shows the land area that is involved in Special Permit development projects and other cases that come before the Planning Board for advice or review.</SPAN></P></DIV></DIV></DIV>

## Purpose
This polygon layer shows the land area that is involved in Special Permit development projects.
## Last Modified
04-06-2026
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|CaseID|type: String<br/>width: 50<br/>precision: 0|Unique ID for Special Permit applications, with letter prefix indicating case type: PB- (Planning Board Special Permit), AHO- (Affordable Housing Overlay Design Review), and PBAC- (Planning Board Advisory Consultation).  Numbers will have three digits, starting with 00 for numbers under 10, and starting with 0 for numbers under 100.|
|CaseType|type: String<br/>width: 100<br/>precision: 0|Full name/description of case type indicated by CaseID prefix: Planning Board Special Permit; Affordable Housing Overlay Design Review; Planning Board Advisory Consultation|
|ProjectName|type: String<br/>width: 50<br/>precision: 0|Name by which the project is known; can be the address if no other moniker is in use|
|MapLots|type: String<br/>width: 100<br/>precision: 0|Map-Lot numbers of affected parcels.  Can be more than one.|
|CaseStatus|type: String<br/>width: 30<br/>precision: 0|Status of the special permit application and project.  Mapped values are Permitting, Reviewing (for AHO), Permitted, Reviewed (for AHO), Under construction, and Built.  Other values (not mapped) include Denied, Expired, No decision, Superseded, and Withdrawn.|
|PolygonType|type: String<br/>width: 30<br/>precision: 0|Source for polygon: Parcel or Building|
|ShowOnWeb|type: SmallInteger<br/>width: 2<br/>precision: 5|Yes/No for whether to display a polygon for the project on the Special Permits web map. For older projects with Status = Built, having  ShowOnWeb = No identifies them as belonging to  separate layer on the web map that can be toggled on and off.|
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
