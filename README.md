The Central GroundWater Board has upwards of 40,000 groundwater monitoring stations across the country
Much of their data on groundwater levels is accessible via [INDIA WRIS](https://indiawris.gov.in/wris/#/DataDownload)
this repo contains code and jupyter notebooks to explore and visualize these datasets and compare them with each other

#Datasets
1) via Tejasvi Hora, U Waterloo
by email from CGWB
this dataset contains state, district, lat, long, site type, well code and Quarterly water level data from 1996 until 2017
2) via [INDIA WRIS](https://indiawris.gov.in/wris/#/DataDownload) 
by selecting Application: Groundwater ; Report Type: State wise Station Level Report (2020-Apr-03)
this dataset contains state, district, station (name), lat, long, station type and monthly/annual groundwater level data (last one to be verified)
3) via [INDIA WRIS](https://indiawris.gov.in/wris/#/DataDownload) 
by pinging the INDIA WRIS geoserver with a WFS request (2020-Apr-03)
this dataset is a shapefile with the locations of all groundwater monitoring stations in the country

#Vision for this project
- compare the various datasets available and document metadata for each
- create some map layers using the raw groundwater level data available
- scraper to download CGWB data for any state and any time period necessary
