# The Power Crisis of February 2021, Houston, Texas


This is a GitHub repository for Jaslyn Miura's analysis of an analysis of the 2021 power crisis after severe winter storms, in Houston, Texas; using NASA's VIIRS, OpenStreetMap, and American Community Survey data.

By analyzing the number of homes and census tracts that experienced an electricity blackout during the winter storms in Houston, Texas, helps us understand if the impacts were disproportionately felt.

##**File Directory:**

```
texas-2021-power-crisis
├── data
│   ├── ACS_2019_5YR_TRACT_48_TEXAS.gdb
│   ├── gis_osm_buildings_a_free_1.gpkg
│   ├── gis_osm_roads_free_1.gpkg
│   └── VNP46A1
├── README.md
├── texas_power_crisis_2021.qmd
└── texas-2021-power-crisis.Rproj
```

data:

- ACS_2019_5YR_TRACT_48_TEXAS: census tracts of Texas data

- gis_osm_buildings_a_free_1: buildings in Texas data

- gis_osm_roads_free_1: roads in Texas data

- VNP46A1: Visible Infrared Imaging Radiometer Suite (VIIRS) satellite data of Houston

texas_power_crisis_2021.qmd: Quarto document with complete code of the analysis.

texas_power_crisis_2021.pdf: Rendered quarto document, as a pdf.

**Data Access:**

The data was accessed through NASA's Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC). Where VIIRS data from February 7th, 2021 and February 16, 2021 of the Houston area were obtained for the analysis. The roads and buildings data were accessed through OpenStreetMap. Census tracts of Texas were obtained through the U.S. Census Bureau's American Community Survey.

**References:**

Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (2021). Visible Infrared Imaging Radiometer Suite [VNP46A1]. NASA. https://ladsweb.modaps.eosdis.nasa.gov/

OpenStreetMap contributors (2025). OpenStreetMap [gis_osm_buildings_a_free_1.gpkg, gis_osm_roads_free_1.gpkg] OpenStreetMap Foundation. Available as open data under the Open Data Commons Open Database License (ODbL) at https://download.geofabrik.de/.

U.S. Census Bureau American Community Survey (2021). [ACS_2019_5YR_TRACT_48_TEXAS.gdb] American Community Survey. https://www.census.gov/programs-surveys/acs


**Author:** 

Jaslyn Miura
            

