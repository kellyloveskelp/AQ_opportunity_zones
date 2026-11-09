# Aquaculture Opportunity Zones off the US West Coast

This analysis determines which Exclusive Economic Zones (EEZ) on the West Coast of the US are best suited to developing marine aquaculture. Suitable locations are determined based on range of suitable sea surface temperature (SST) and depth values for the aquacultured species.

Contents

| Folder | Housing | Description |
|-------------------|-------------------|-----------------------------------|
| data/sst/ | [NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php) | Sea Surface Temperature (SST) rasters from 2008-2012 derived from a combination of satellite imagery |
| data/depth.tif | [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area) | Global terrain model .tif for ocean and land, providing elevation data, in meters, on a 15 arc-second interval grid provided by International Hydrographic Organization(IHO) and the Intergovernmental Oceanographic Commission (IOC) (of UNESCO) |
| data/wc_regions_clean.shp | [Marineregions.org](https://www.marineregions.org/eez.php) | Vector layer of Exclusive Economic Zones (EEZs) around the globe |
| aq_opportunity_zones.qmd | This repo | R script that creates function to process rasters and rasterize vector data |

## Data Citations

| Source | Citation | Link |
|------------------------|------------------------|------------------------|
| SeaLifeBase | Worldwide database on aquatic species reports | <https://www.sealifebase.ca/search.php> |
| The Olympia Oyster | Caldwell, Ian. The Olympia Oyster. *Coastal Interpretive Center News* (October 19, 2023). | <https://www.interpretivecenter.org/news/the-olympia-oyster> |
| Gentry et al. 2017 | Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M., Rust, M., Gaines, S. D., & Halpern, B. S. Mapping the global potential for marine aquaculture. *Nature Ecology & Evolution*, 1, 1317-1324 (2017). | <https://www.nature.com/articles/s41559-017-0257-9> |