## 2021 Houston power crisis: identifying the impacts of extreme weather

### Purpose

This repository explores the effects of the February 2021 winter storms in Texas. Specifically, it looks at the impact and distribution of homes in the Houston area that lost power.

![Texas ice storm](images/texas.jpg)

### Repository structure

```bash
la_holc_EJ_impacts
│
├── .gitignore 
├── data                        
│   ├── gis_osm_buildings_a_free_1.gpkg
│   ├── gis_osm_roads_free_1.gpkg
│   ├── ACS_2019_5YR_TRACT_48_TEXAS.gdb
│   ├── VNP46A1
│ 
├── images                      
│   ├── texas.jpg
│
├── houston_power_crisis.files
│     ├── figure-html
│     ├── libs
│
├── houston_power_crisis.html
├── houston_power_crisis.qmd
├── houston_power_crisis.Rproj
├── README.md  
│
```

### Data

The night lights data comes from NASA's Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC).

The roads and houses data comes from OpenStreetMap (OSM), a collaborative project that produces freely accessible geographic data of the entire world.

The socioeconomic data comes from the US Census Bureau's American Community Survey. The folder is an ArcGIS file geodatabase.

### Authors and contributors

Liz Peterson

Contributor: Dr. Ruth Oliver wrote this assignment for EDS 223: Geospatial Analysis & Remote Sensing

### Sources

1. Wikipedia. 2021. “2021 Texas power crisis.” Last modified October 2, 2021. https://en.wikipedia.org/wiki/2021_Texas_power_crisis.↩︎

2. Geofabrik GmbH and OpenStreetMap Contributors. (2018). OpenStreetMap Data. Retrieved from https://www.geofabrik.de.

3. U.S. Census Bureau. (n.d.). American Community Survey. U.S. Department of Commerce. Retrieved from https://www.census.gov/programs-surveys/acs
