# RhodeIsland
Voronoi map of hospitals providing stroke services in Rhode Island, USA. The Voronoi map is written such that any point within each voronoi (colored) cell is closest to the seed (hospital). It illustrates the points that large change to the system is required to improve delivery of stroke care. In this map, some hospitals are closer to counties in adjacent states. Also if patients are transported to the nearest hospital, then a lot of cases would have been taken to adjacent Primary Stroke Centre (PSC) rather than the Comprehensive Stroke Centre (CSC). PSC can provide clot busting therapy whereas CSC are capable of providing clot busting and clot extraction (thrombectomy).
Uses deldir to create voronoi, and awesome icons for markers, ggmap for geocoding, leaflet for making map.
new ggmap users should obtain key from Google Maps API
the shape file comes from tiger 2019 data-https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html
code is provided in Rmd file, geocode data on hospitals in Rhode Island is provided in excel file
