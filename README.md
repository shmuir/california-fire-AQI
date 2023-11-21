# Air quality and Fire extent in Santa Barbara County in 2017-2018

This is a final project for EDS220: Working With Environmental Datasets for the Masters of Environmental Data Science program at the Bren School at UCSB. 

The goal of this project is to become more comfortable working with environmental and spatial data in Python by using air quality and fire data to look at the effects of the Thomas Fire in Santa Barbara County. This includes:

1. Reading in the various datasets
2. Plotting the extent of fires in Santa Barbara County, CA in 2017
3. Analyzing differences in the Air Quality Index (AQI) over 2017-2018 as a time series plot

### Data Citations

California State Geoportal. 2019. California Fire Perimeters (all). https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about.

Environmental Protection Agency. Air Quality Index. https://www.airnow.gov/aqi/aqi-basics/

Microsoft Planetary Computer. Landsat Collection 2 Level-2. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2#overview

### File Structure

    california-fire-AQI
    │   README.md
    │   ca_fires_aqi.ipynb    
    │
    └───data
        │   California_Fire_Perimeters_2017
        |   │   fire shapefiles
        │   landsat8-2018-01-26-sb-simplified.nc

