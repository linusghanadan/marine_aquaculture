# Marine aquaculture species suitability for U.S. West Coast
## Purpose
This analysis seeks to build on knowledge regarding the potential for marine aquaculture expansion in the four Exclusive Economic Zones (EEZs) adjacent to the U.S. West Coast. Using raster data on mean sea surface temperature and depth, I’ll estimate the total and percent area within each of these four EEZs that would be suitable for oyster aquaculture. After visualizing oyster suitability, I’ll create a generalized model that can be used for any species based on their ideal temperature and depth ranges.

## Repository contents
    marine_aquaculture
    │   README.md
    │   .gitignore
    │   .Rmd
    │   .Rproj   
    │   .html

## Datasets
1. Sea surface temperature TIF files
2. Bathymetry raster
3. Shapefile for West Coast EEZs

## Data references
1. National Oceanic and Atmospheric Association (NOAA). 2018. “Daily Global 5km Satellite Sea Surface Temperature Anomaly.” https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php.
2. General Bathymetric Chart of the Oceans (GEBCO). 2023. “Gridded Bathymetry Data.” https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area.
3. Marine Regions. n.d. “EEZ Boundaries.” https://www.marineregions.org/eez.php.

## Notes on accessing data
Data used in this analysis was stored locally and included in repositiory .gitignore file. Use data references to access the original data.
