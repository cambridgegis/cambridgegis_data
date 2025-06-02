# Trees
## GIS File Name
ENVIRONMENTAL_StreetTrees
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN><SPAN>Trees and tree planting sites owned, planted or maintained by the City of Cambridge, the Massachusetts Department of Conservation and Recreation, and MIT, Harvard University and other private organizations. This layer is maintained by Cambridge Public Works</SPAN></SPAN></P></DIV></DIV></DIV>

## Purpose
City owned and maintained trees. This layer is maintained by Cambridge Public Works and updated regularly by the City Arborist. 
## Last Modified
06-02-2025
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|creator|type: String<br/>width: 40<br/>precision: 0|Name of the editor who created the record.|
|inspectr|type: String<br/>width: 40<br/>precision: 0|Name of the tree inspector.|
|species|type: String<br/>width: 30<br/>precision: 0|Common name of the species of the current tree.|
|diameter|type: Single<br/>width: 4<br/>precision: 6|Tree diameter in inches taken at approximately 4.5 feet above ground (DBH). If the diameter point falls on a swelling in the trunk it is customary to measure below the swelling at the point where the diameter is smallest. Note: an average diameter should be calculated for trees with multiple trunks (see the Trunks field); an online calculator for multi-stemmed trees may be found at https://www.treetec.net.au/TPZ_SRZ_DBH_calculator.php.|
|trunks|type: SmallInteger<br/>width: 2<br/>precision: 5|Number of tree trunks (see note at Diameter about using the number of trunks to calculate an average tree diameter).|
|notes|type: String<br/>width: 500<br/>precision: 0|Miscellaneous notes.|
|SiteType|type: String<br/>width: 20<br/>precision: 0|Designates whether the site is currently occupied by a tree (Tree) or stump (Stump), is an empty planting site (Planting  Site), or has been paved over or is otherwise empty and no longer available for planting (Retired). Note: this field typically supersedes any conflicting data within the record; for example, a record designated as a “Planting Site” would indicate that any values for Diameter and Trunks were no longer valid.|
|PlantDate|type: Date<br/>width: 8<br/>precision: 0|Date that a tree was last planted at this site.|
|RemovalDate|type: Date<br/>width: 8<br/>precision: 0|Date that a tree was last removed from this site.|
|SpeciesShort|type: String<br/>width: 50<br/>precision: 0|Genus of the current tree species (see Species).|
|TreeID|type: String<br/>width: 50<br/>precision: 0|Unique identifier for the record.|
|OverheadWires|type: SmallInteger<br/>width: 2<br/>precision: 5|Designates the presence of above-ground utility wires in the area of tree canopy growth at the site.|
|Cultivar|type: String<br/>width: 50<br/>precision: 0|Cultivated variety of the current tree species (see Species).|
|StreetNumber|type: SmallInteger<br/>width: 2<br/>precision: 5|Number of the street address closest to the site.|
|StreetName|type: String<br/>width: 40<br/>precision: 0|Name of the street for the address closest to the site.|
|MemTree|type: String<br/>width: 1<br/>precision: 0|Designates whether the current tree was planted in memoriam.|
|Location|type: String<br/>width: 50<br/>precision: 0|Designates whether the site is located along a street (Street Tree), beyond the back edge of a sidewalk in a front yard or other area not immediately adjacent to a street (Back of Sidewalk), in a park or other open space (Park Tree, Cemetery Tree, Golf Course), or on the grounds of a public school or other municipal building (Public School, City Building).|
|Ownership|type: String<br/>width: 50<br/>precision: 0|Designates the ownership of the tax parcel on which the site falls.|
|ADACompliant|type: String<br/>width: 1<br/>precision: 0|Designates whether the site is ADA compliant, for instance whether the site has the minimum required sidewalk width of 4 feet.|
|TreeGrateActionReq|type: SmallInteger<br/>width: 2<br/>precision: 5|This field is used to record if the metal tree grate surrounding the tree needs to be reset or removed.  When the tree grows, it can get girdled by the tree grate.|
|BareRoot|type: String<br/>width: 3<br/>precision: 0|Designates whether the last tree was planted as a bare-root tree.|
|TreeWellCover|type: String<br/>width: 25<br/>precision: 0|The type of cover, if any that is over the tree well. The two values are Tree Grate or Flexi-Pave.|
|StructuralSoil|type: String<br/>width: 5<br/>precision: 0|Indicates if the tree was planted in structural soil.|
|TreeWellLength|type: Double<br/>width: 8<br/>precision: 38|The length of the tree well.|
|TreeWellWidth|type: Double<br/>width: 8<br/>precision: 38|The width of the tree well.|
|AbutsOpenArea|type: String<br/>width: 5<br/>precision: 0|Indicates if the tree abuts an open space or if the tree well is the only open area around the tree.|
|ExposedRootFlare|type: String<br/>width: 5<br/>precision: 0|Indicates if the root flare of the tree is visible.|
|TreeWellID|type: Integer<br/>width: 4<br/>precision: 10||
|created_user|type: String<br/>width: 255<br/>precision: 0||
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|Genus|type: String<br/>width: 55<br/>precision: 0||
|last_edited_user|type: String<br/>width: 255<br/>precision: 0|Initials of person making most recent edit|
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0|Last edit date.|
|CommonName|type: String<br/>width: 55<br/>precision: 0||
|CartegraphRetireDate|type: Date<br/>width: 8<br/>precision: 0||
|CartegraphPlantDate|type: Date<br/>width: 8<br/>precision: 0||
|ScientificName|type: String<br/>width: 55<br/>precision: 0||
|Order_|type: String<br/>width: 30<br/>precision: 0||
|PlantingContract|type: String<br/>width: 30<br/>precision: 0||
|WateringResponsibility|type: String<br/>width: 25<br/>precision: 0||
|LocationRetired|type: String<br/>width: 3<br/>precision: 0||
|SiteReplanted|type: String<br/>width: 3<br/>precision: 0||
|SiteRetiredReason|type: String<br/>width: 255<br/>precision: 0||
|Biochar_Added|type: String<br/>width: 3<br/>precision: 0||
|SolarRating|type: SmallInteger<br/>width: 2<br/>precision: 5|Solar radiation rating between 1 and 5, where 1 is the lowest score and 5 is the highest (receives the most light). Pictometry 2014 DSM and DEM were used to determine tree height and measure shadows from 2014 3D buildings. SolarRating is the average of the solar radiation for both the DSM and DEM results for June, July, August, and September.|
|TreeWellDepth|type: Double<br/>width: 8<br/>precision: 38||
|ScheduledRemoval|type: SmallInteger<br/>width: 2<br/>precision: 5||
|RemovalReason|type: String<br/>width: 25<br/>precision: 0||
|PB|type: String<br/>width: 3<br/>precision: 0||
|PlantingSeason|type: String<br/>width: 15<br/>precision: 0||
|StTreePruningZone|type: String<br/>width: 10<br/>precision: 0||
|OffStTreePruningZone|type: String<br/>width: 10<br/>precision: 0||
