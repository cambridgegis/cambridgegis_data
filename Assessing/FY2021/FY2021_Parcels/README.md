# FY2021 Parcels
## Property Database Metadata ##
The following fields are contained in the property database table.

|Field Name | Description |  
|-----------|-------------|  
|PID | Internal Unique Parcel ID |  
|GISID | Link to ML in GIS Parcels layer |  
|BldgNum | Building Number on Parcel |  
|Address | Parcel Address |  
|Unit | Unit Number |  
|StateClassCode | State Classification Code |  
|PropertyClass | Classification Code description |  
|Zoning | Zoning (Unofficial) |  
|Map/Lot | Assessor's Map and Lot ID |  
|LandArea | Land area in square feet |  
|YearOfAssessment | Fiscal Year of Assessment for this record |  
|TaxDistrict | District for valuation grouping |  
|ResidentialExemption | Receiving Residential exemption for fiscal year |  
|BuildingValue | Assessed value of building improvements on the parcel |  
|LandValue | Assessed value of land on the parcel |  
|AssessedValue | Total assessed value |  
|SalePrice | Price listed for last deed transfer for the parcel |  
|Book/Page | Book and Page number from the registry of deeds for last deed transaction |    
|SaleDate | Date of last deed transaction |  
|PreviousAssessedValue | Total assessed value for the prior fiscal year |    
|Owner_Name | Name of owner of record for the date of assessment |    
|Owner_CoOwnerName | Name of co-owner of record for the date of assessment |  
|Owner_Address | Address of owner of record for the date of assessment |  
|Owner_Address2 | Second line of address of owner of record for the date of assessment |  
|Owner_City | City of owner of record for the date of assessment |  
|Owner_State | State of owner of record for the date of assessment |  
|Owner_Zip | Zip code of owner of record for the date of assessment |    
|Exterior_Style | Building style description |  
|Exterior_occupancy | Building occupany, or use, type description |  
|Exterior_NumStories | Number of stories for the building |  
|Exterior_WallType | Exterior wall material description |  
|Exterior_WallHeight | Average height of floors in a commercial or apartment building |  
|Exterior_RoofType | Roof structure description |  
|Exterior_RoofMaterial | Roof material description |  
|Exterior_FloorLocation | Floor level for condominium units |  
|Exterior_View | View quality rating for condominiums |  
|Interior_LivingArea | Finished area of building |  
|Interior_NumUnits | Number of units in a commercial or apartment building |  
|Interior_TotalRooms | Total number of rooms in a condominium or residential building |  
|Interior_Bedrooms | Total number of bedrooms in a condominium or residetential building |  
|Interior_Kitchens | Kitchen description in condominium unit |  
|Interior_FullBaths | Count of full bathrooms in a condominium unit or residential building |  
|Interior_HalfBaths | Count of half bathrooms in a condominium unit or residential building |  
|Interior_Fireplaces | Count of fireplaces in residential buildings |  
|Interior_Flooring | Description of primary floor cover material |  
|Interior_Layout | Layout description for condominium unit |  
|Interior_LaundryInUnit | Yes or No flag for in unit laundry for condominium |  
|Systems_HeatType | Heat system type description |  
|Systems_HeatFuel | Heat fuel type description |  
|Systems_CentralAir | Central air conditioning system indicator |  
|Systems_Plumbing | Rating of plumbing system for commercial building |  
|Condition_YearBuilt | Actual year built of building |  
|Condition_InteriorCondition | Description of interior condition of residential building |  
|Condition_OverallCondition | Description of overall condition of building |  
|Condition_OverallGrade | Description of overall grade of building |  
|Parking_Open | Number of open parking spaces for residential building or condominium unit |  
|Parking_Covered | Number of covered parking spaces for residential building or condominium unit |  
|Parking_Garage | Number of garage parking spaces for residential building or condominium unit |  
|UnfinishedBasementGross | Unfinished basement area |  
|FinishedBasementGross | Finished basement area |  ## GIS File Name
ASSESSING_ParcelsFY2021
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This polygon layer contains all of the property parcels in Cambridge. Each parcel has a unique Map and Lot ID number that links it to a record in the Assessing Department's Vision database system. </SPAN></P></DIV></DIV></DIV>

## Purpose
Created for internal use by the Assessing Department to provide a visual reference associated with each parcel in the CAMA database. Created for interdepartmental and external use as part of the web viewers on the City's website. Also created for addressing/geocoding needs, although the Buildings and Master Address List are currently more accurate than Parcels. 

NOTE: The Parcels GIS data layer is NOT used by Assessing to calculate land area or taxes. Assessors refer to actual deeds or plans accepted by the Massachusetts Land Court. The figures stored in the GIS data layer are for general reference purposes only.
## Last Modified
10-06-2020
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|ML|type: String<br/>width: 16<br/>precision: 0|Map and Lot numbers separated by "-"|
|MAP|type: String<br/>width: 5<br/>precision: 0|Map (block) number|
|LOT|type: String<br/>width: 5<br/>precision: 0|Lot (parcel) number|
|UYEAR|type: Integer<br/>width: 4<br/>precision: 0||
|Editor|type: String<br/>width: 20<br/>precision: 0|Initials of person making most recent edit|
|EditDate|type: Date<br/>width: 8<br/>precision: 0|Date of most recent edit|
|LOC_ID|type: String<br/>width: 18<br/>precision: 0||
|POLY_TYPE|type: String<br/>width: 15<br/>precision: 0||
|SOURCE|type: String<br/>width: 15<br/>precision: 0||
|PLAN_ID|type: String<br/>width: 40<br/>precision: 0||
|created_date|type: Date<br/>width: 8<br/>precision: 0||
|last_edited_date|type: Date<br/>width: 8<br/>precision: 0||
|SHAPE_Length|type: Double<br/>width: 8<br/>precision: 0|Length of feature in internal units.|
|SHAPE_Area|type: Double<br/>width: 8<br/>precision: 0|Area of feature in internal units squared.|
