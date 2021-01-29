#### Harmonizing Aboveground Global Biomass (HAGB) Dataset
Source: Oak Ridge National Laboratory; Spawn and Gibbs (2020)
Location: https://doi.org/10.3334/ORNLDAAC/1763
Domain: Global, 2010
Resolution: 300m

Summary: This dataset provides temporally consistent and harmonized global maps of aboveground and belowground biomass carbon density for the year 2010 at a 300-m spatial resolution. The aboveground biomass map integrates land-cover specific, remotely sensed maps of woody, grassland, cropland, and tundra biomass. Input maps were amassed from the published literature and, where necessary, updated to cover the focal extent or time period. The belowground biomass map similarly integrates matching maps derived from each aboveground biomass map and land-cover specific empirical models. Aboveground and belowground maps were then integrated separately using ancillary maps of percent tree cover and landcover and a rule-based decision tree. Maps reporting the accumulated uncertainty of pixel-level estimates are also provided.

## Storage resources
Data are stored in blobs in the West US data center, in the following blob container:

https://carbonplan.blob.core.windows.net/carbonplan-data/raw/2010-harmonized-biomass/global/300m/

Images are stored in cloud optimized GeoTIFF format. 

A complete Python example of accessing and plotting HAGB data is available in the notebook provided under “data access”.
