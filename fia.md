# Forest Inventory and Analysis

Source: US Forest Service

Source Location: https://www.fia.fs.fed.us/

Domain: Continental US, 1928-2018

Resolution: plot-level (irregular polygon)

Data on status and trends in forest location, health, growth, mortality, and production.

The Forest Inventory and Analysis (FIA) dataset is a nationwide survey of the forest assets of the United States. The Forest Inventory and Analysis research program has been in existence since mandated by Congress in 1928. FIA's primary objective is to determine the extent, condition, volume, growth, and use of trees on the Nation's forest land.

## Storage resources
Data are stored in blobs in the West US data center, in the following blob container:

https://carbonplan.blob.core.windows.net/carbonplan-data/raw/fia

Within that container, data are organized according to:

/[table].parquet

`table` is one of the FIA tables:

- boundary
- cond
- cond_dwm_calc
- county
- dwm_coarse_woody_debris
- dwm_duff_litter_fuel
- dwm_fine_woody_debris
- dwm_microplot_fuel
- dwm_residual_pile
- dwm_transect_segment
- dwm_visit
- grnd_cvr
- invasive_subplot_spp
- lichen_lab
- lichen_plot_summary
- lichen_visit
- ozone_biosite_summary
- ozone_plot
- ozone_plot_summary
- ozone_species_summary
- ozone_validation
- ozone_visit
- p2veg_subp_structure
- p2veg_subplot_spp
- plot
- plot_regen
- plotgeom
- plotsnap
- pop_estn_unit
- pop_eval
- pop_eval_attribute
- pop_eval_grp
- pop_eval_typ
- pop_plot_stratum_assgn
- pop_stratum
- seedling
- seedling_regen
- sitetree
- soils_erosion
- soils_lab
- soils_sample_loc
- soils_visit
- subp_cond
- subp_cond_chng_mtrx
- subplot
- subplot_regen
- survey
- tree
- tree_grm_begin
- tree_grm_component
- tree_grm_estn
- tree_grm_midpt
- tree_grm_threshold
- tree_regional_biomass
- tree_woodland_stems
- veg_plot_species
- veg_quadrat
- veg_subplot
- veg_subplot_spp
- veg_visit.parquet

Tables are stored in Parquet datasets. 

A complete Python example of accessing and plotting a FIA data is available in the notebook provided under “data access”.
