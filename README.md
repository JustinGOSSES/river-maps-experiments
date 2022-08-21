# river-maps-experiments
place to play around making maps of rivers to try a few things

## Data

The data folder if not pushed to origin to avoid storage fees. 

There will be a bias towards datasets that exist at national scale that can be downloaded in smaller pieces based on lat/long location. These datasets will enable replicating the approach in Houston to anywhere else in the continental United States.

#### Galveston Harris County Area H-GAC Council Datasets

All these were from: https://gishub-h-gac.hub.arcgis.com/ ...and in general gac datasets seem to have been poor quality so ignoring
- USCB_Urban_Areas_2010.geojson
- USGS_HUC_10_Watersheds.geojson
- USGS_HUC_12_Subwatersheds.geojson
- HGAC_Major_Rivers.geojson


#### River Health Datasets

Lots of interesting mapping of river health that might be cool to extract here: https://h-gac.maps.arcgis.com/apps/MapSeries/index.html?appid=30b802d67f5d4a2aa7915cc30bca9318 However, this is local data only.


#### Land Cover Datasets
Might also look at this 100m resolution land cover of USA from UT library https://geodata.lib.utexas.edu/catalog/stanford-sw186vh2473

Or the USGS land cover USA: https://www.usgs.gov/centers/eros/science/national-land-cover-database

Unsure if this map will allow export but it does have good Harris and Galveston county Land Use details: https://datalab.h-gac.com/RLUIS/

The Microsoft + ESRI landcover raster data ended up working well for land cover 9-10 classes. 

#### Ecosystems Datasets

It would be nice to get the ecosystems data at CONUS scale working at some point as that's more interesting than just land cover. 

#### Digitial Elevation Model Datasets

USGS national scale DEM seem like a good option: https://www.sciencebase.gov/catalog/item/6184ba68d34ec04fc9c08131 & https://apps.nationalmap.gov/downloader/

Other Digita elevation data sources are mentioned in this repository if needed: https://github.com/OpenTopography/RiverREM

## Potential New Data Sources
- Open Street Map API Helper: https://github.com/gboeing/osmnx

## Interesting Examples

### Trains & Trails
- link: https://rreusser.github.io/trains-and-trails/reinhardt-redwood-regional-park/
- repo-link: https://github.com/rreusser/trains-and-trails
- why-interesting: Has a map path view in 3D overlaid as well as elevation model & time with pictures timeline that are all connected and navigated via scroll. 

### Percent Change in Land User by County Web Page Interactive by USGS
https://www.mrlc.gov/eva/

## Experience Brainstorming

### Data to plot PER river or ALONG river
- Land Cover
- ecosystems
- Elevation
- bridges?
- parks?
- Straight vs. Curves?
- Number of curves?

### Visualizations
 
#### Comparison of Multiple Rivers
Comparison between X rivers at one time?


#### Along River Visualizations
Visualization of changes ALONG one river, possibly along a path or between two or more points?


### User Interface Experience


### Users 
- Paddlers
  - Trying to understand where they could go paddling in an area and how the rivers differ
  - Trying to undersrtand how a potential trip would differ in different parts of the river
  - Trying to understand the differences between many different rivers or different trips.


### Existing Resources for Similar Users with Similar Tasks
#### Houston Scope
- https://www.bayoupreservation.org/ (bayou preservation)
- http://www.savebuffalobayou.org/?page_id=4909 (bayou preservation)
- https://bayoucitywaterkeeper.org/ (bayou preservation)
- https://cechouston.org/state-of-the-environment-2006/water-quality/ (bayou preservation)
- https://www.hcfcd.org/ (Harris County Flood Control District)
- https://www.harriscountyfws.org/ (Harris County Flood Warning System)

#### Texas Scope
- https://tpwd.texas.gov/fishboat/boat/paddlingtrails/ (Texas Parks and Wildlife Paddling Trails)

#### National Scope
- https://paddling.com/paddle/locations? (Paddling Locations Map)
  - example: https://paddling.com/paddle/trips/sea-rim-state-park-texas
- https://riverweather.com/riverstages/houston/ (spreadsheet style view of river height trends)

### User Interface Components


### Data Processing Components

#### Data Processing Data Types


#### Data Processing Tools



#### How to Replicate, Scale, Store, Etc.
