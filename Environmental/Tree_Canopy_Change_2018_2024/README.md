# Tree Canopy Change 2018 2024

> [!IMPORTANT]  
> The 2018-2024 Tree Canopy Change file is too big for for our GitHub tier. Please see [Tree Canopy Change 2018 2024](https://www.cambridgema.gov/gis/gisdatadictionary/environmental/environmental_treecanopychange_2018_2024) in our data dictionary for other download options.

## GIS File Name
UrbanForestry_TreeCanopyChange_2018_2024
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This layer is a high-resolution tree canopy change-detection layer for Cambridge, MA. It contains three tree-canopy classes for the period 2018-2024: (1) No Change; (2) Gain; and (3) Loss. It was created by extracting tree canopy from existing high-resolution land-cover maps for 2018 and 2024 and then comparing the mapped trees directly. Tree canopy that existed during both time periods was assigned to the No Change category while trees removed by development, storms, or disease were assigned to the Loss class. Trees planted during the interval were assigned to the Gain category, as were the edges of existing trees that expanded noticeably. Direct comparison was possible because both the 2018 and 2024 maps were created using object-based image analysis (OBIA) and included similar source datasets (LiDAR-derived surface models, multispectral imagery, and thematic GIS inputs). OBIA systems work by grouping pixels into meaningful objects based on their spectral and spatial properties, while taking into account boundaries imposed by existing vector datasets. Within the OBIA environment a rule-based expert system was designed to effectively mimic the process of manual image analysis by incorporating the elements of image interpretation (color/tone, texture, pattern, location, size, and shape) into the classification process. A series of morphological procedures were employed to insure that the end product is both accurate and cartographically pleasing. No accuracy assessment was conducted, but the dataset will be subjected to manual review and correction at a scale of 1:2500.</SPAN></P></DIV></DIV></DIV>

## Purpose
This dataset was developed as part of an Urban Tree Canopy (UTC) assessment for Cambridge, MA. It shows how tree canopy changed during the period 2018-2024, highlighting trees that were gained or lost during the 6-year period. It is intended for use in monitoring patterns of change in Cambridge, MA tree canopy.
## Last Modified
09-14-2026
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|Class_name|type: String<br/>width: 255<br/>precision: 0|Classification name. Contains three tree-canopy classes for the period 2009-2014: (1) No Change; (2) Gain; and (3) Loss|
