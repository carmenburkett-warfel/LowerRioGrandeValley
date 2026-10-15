# LowerRioGrandeValley
Spatial datasets for the Lower Rio Grande Valley, Texas, USA

Abbreviations used throughout:
* LRGV = Lower Rio Grande Valley
* NWR = National Wildlife Refuge
* WMA = Wildlife Management Area
* SP = State Park
* LA = Laguna Atascosa
  
This repository contains spatial datasets of protected areas in the Lower Rio Grande Valley (LRGV) of southern Texas, including Willacy, Cameron, Hidalgo, Starr, and Zapata counties. The repository also contains the R code used to create the spatial datasets.

All protected-area polygons were created in R using the sf package, based on regional maps and U.S. Fish and Wildlife Service (USFWS) documentation. Additional attributes were added in ArcGIS Pro.

The datasets are provided in three formats to accommodate different research and mapping needs:
1) Individual protected-area units: Individual tracts or units are available separately and organized into folders by refuge, state park, wildlife management area, or other protected-area type. This format allows users to select specific units for their analyses.

2) Regional layer retaining individual units: A single layer containing the protected areas across the LRGV, with individual tracts or units maintained as separate features.
   
3) Regional layer with dissolved protected areas: A single layer containing protected areas dissolved into larger units, such as entire refuges, rather than retaining individual tract boundaries and attributes.

Although these datasets represent the same protected areas, the way polygons are grouped and their attributes are retained differs among versions. Users can select the format that best suits their research or GIS workflow.
