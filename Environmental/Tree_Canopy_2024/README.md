# Tree Canopy 2024

> [!IMPORTANT]  
> The 2024 Tree Canopy file is too big our GitHub tier. Please see [Tree Canopy 2024](https://www.cambridgema.gov/gis/gisdatadictionary/environmental/environmental_treecanopy2024) in our data dictionary for other download options.

## GIS File Name
UrbanForestry_TreeCanopy2024
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This dataset represents tree objects derived from LiDAR data. Tree objects are the approximated delineation of a tree's branches and leaves in the source LiDAR data. The mapping of tree objects was constrained to those areas of tree canopy, using the tree canopy dataset developed separately for this project, which employed automated techniques coupled with manual editing to extract tree canopy from imagery and LiDAR. Mapping of tree objects was performed using an automated feature extraction technique that incorporated segmentation and morphology routines. The automated routine first created objects from the tree canopy using an inverse watershed segmentation algorithm applied to the LiDAR nDSM (normalized digital surface model). These objects were then refined using the spatial properties of the objects. Attributes include the tree height and radius. The height was calculated using the 98th quantile of the LiDAR nDSM height to reduce outlier values. The radius was then calculated from the tree centroid using the formula (Cambridge, MA/P)^0.5.</SPAN></P></DIV></DIV></DIV>

## Purpose
This dataset is designed to be used to represent the location of trees, their height, and associated crown characteristics.
## Last Modified
09-14-2026
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|Radius|type: Double<br/>width: 8<br/>precision: 38||
|Height_ft|type: Double<br/>width: 8<br/>precision: 38||
