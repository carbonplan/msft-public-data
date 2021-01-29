# MTBS Burn Severity Mosiacs

Annual burn severity mosaics for the continental United States and Alaska.

Monitoring Trends in Burn Severity (MTBS) is an interagency program whose goal is to consistently map the burn severity and extent of large fires across all lands of the United States from 1984 to present. This includes all fires 1000 acres or greater in the western United States and 500 acres or greater in the eastern Unites States. The extent of coverage includes the continental U.S., Alaska, Hawaii and Puerto Rico.

The burn severity mosaics consist of thematic raster images of MTBS burn severity classes for all currently completed MTBS fires for the continental United States, Alaska, Hawaii and Puerto Rico. Mosaicked burn severity images are compiled annually for each year by US State and the continental United States.

## Storage resources
Data are stored in blobs in the West US data center, in the following blob container:

https://carbonplan.blob.core.windows.net/carbonplan-data/raw/mtbs

Within that container, data are organized according to:

[region]/30m/severity/[year].tif

`region` is the spatial domain; currently `conus` or `ak`.

`year` is four digit year (e.g. 2017)

Images are stored in cloud optimized GeoTIFF format. 

A complete Python example of accessing and plotting a MTBS data is available in the notebook provided under “data access”.
