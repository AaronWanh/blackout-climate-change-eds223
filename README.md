# Homework Assignment 3

In this assignment, we explore the effects of three severe winter storms particularly in Texas when they suffered from a major power crisis. Our goal is identify the impacts of the storms by estimating the number of homes that lost power in Houston and observe whether these impacts were disproportionately experienced. By conducting spatial analysis on the level of radiance in Houston between 2021-02-07 and 2021-02-16, we can observe how the night lights in Houston changed before and after the storm occurred. Then we can compare the spatial regions with low radiance to the homes that experienced blackouts. Because highways produce high levels of radiance, implementing a buffer 200 meters around the highways is important so that the radiance of the cars is not considered when studying overall radiance from homes. 

## Inside the Repo:

This repository contains a data folder that holds 4 different VNP46A1 satellite data with a horizontal and vertical grid position for 02-07 and 02-16. We also have a Geopackage file that showcases the roads and houses in Houston. However we have a gitignore file to prevent the large dataset from bloating the repository. The main code and graphs are within the quarto document hw4.qmd. Finally the README.md file is a summary of what is contained inside the repository and what it accomplishes. 

```text
C:.
|   .gitignore
|   hw4.qmd
|   README.md
|   
\---data
    |   gis_osm_buildings_a_free_1.gpkg
    |   gis_osm_roads_free_1.gpkg
    |   
    \---VNP46A1
            VNP46A1.A2021038.h08v05.001.2021039064328.tif
            VNP46A1.A2021038.h08v06.001.2021039064329.tif
            VNP46A1.A2021047.h08v05.001.2021048091106.tif
            VNP46A1.A2021047.h08v06.001.2021048091105.tif
```

## Authors/Collaborators:
- Aaron Wang
- Annie Adams https://github.com/annieradams 


## Citations:
* Román, M. O. (2018). VIIRS/NPP daily gridded day night band 500m linear lat lon grid night (VNP46A1), version 1 [Data set]. NASA Level-1 and Atmosphere Archive and Distribution System Distributed Active Archive Center (LAADS DAAC). https://doi.org/10.5067/VIIRS/VNP46A1.001
* Geofabrik GmbH. (n.d.). OpenStreetMap data extracts: Texas roads [Data set]. https://download.geofabrik.de/
* Geofabrik GmbH. (n.d.). OpenStreetMap data extracts: Texas buildings [Data set]. https://download.geofabrik.de/
