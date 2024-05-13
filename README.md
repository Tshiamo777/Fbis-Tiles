This file contains styled Vector Tile layers from the Freshwater Biodiversity Information System. This repo does not contain the original FBIS tiles file.

A few things to note:
- Hydro Region flow type - uses numbers, im assuming it relates to flow regime type in qgis. Field values in Qgis are rounded over.
- SA Veg map, Fbis model does not correlate with the tiles layer. Bioregions are different in Qgis

Layers that dont load in the editor:
- SA National land cover, investigate symbols
- LADA land use
- Ecoregion level 2
- Ecological support
- surface water source, some layers load
- artificial wetlands
- im assuming this is due to zoom level, i was able to get around the issue by playing around with the zoom level while styling

Layers i cant find in the FBIS file:
- shulze
- site
- water management areas
- river management units
- River Management units
- conservation areas
- NFEPA fish sanctuaries
- KG climate zones
