#### National Land Cover Databse (NLCD)
Source: U.S. Geological Survey (USGS)
Location: https://www.mrlc.gov/
Domain: Continental US, 2001-2016
Resolution: 30 m

Summary: The U.S. Geological Survey (USGS), in partnership with several federal agencies, has developed and released four National Land Cover Database (NLCD) products over the past two decades: NLCD 1992, 2001, 2006, and 2011. These products provide spatially explicit and reliable information on the Nation’s land cover and land cover change. To continue the legacy of NLCD and further establish a long-term monitoring capability for the nation’s land resources, the USGS has designed a new generation of NLCD products named NLCD 2016. The NLCD 2016 design aims to provide innovative, consistent, and robust methodologies for production of a multi-temporal land cover and land cover change database from 2001 to 2016 at 2–3-year intervals. Comprehensive research was conducted and resulted in developed strategies for NLCD 2016: a streamlined process for assembling and preprocessing Landsat imagery and geospatial ancillary datasets; a multi-source integrated training data development and decision-tree based land cover classifications; a temporally, spectrally, and spatially integrated land cover change analysis strategy; a hierarchical theme-based post-classification and integration protocol for generating land cover and change products; a continuous fields biophysical parameters modeling method; and an automated scripted operational system for the NLCD 2016 production. The performance of the developed strategies and methods were tested in twenty World Reference System-2 path/row throughout the conterminous U.S. An overall agreement ranging from 71% to 97% between land cover classification and reference data was achieved for all tested area and all years. Results from this study confirm the robustness of this comprehensive and highly automated procedure for NLCD 2016 operational mapping.

## Storage resources
Data are stored in blobs in the West US data center, in the following blob container:

https://carbonplan-data.blob.core.windows.net/carbonplan-data/raw/nlcd/

Within that container, data are organized according to:

[region]/30m/[year].tif

`region` is the spatial domain; currently `conus` or `ak`.

`year` is four digit year (e.g. 2014)

Images are stored in cloud optimized GeoTIFF format. 

A complete Python example of accessing and plotting MTBS data is available in the notebook provided under “data access”.