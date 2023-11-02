
# Geospatial Analysis with GeoPandas: Boston's WiFi Locations

## Description
This Jupyter Notebook performs a geospatial analysis focusing on the WiFi locations around the city of Boston using the GeoPandas library. It demonstrates how to visualize, clean, and manipulate geospatial data effectively.

## Datasets

- 2020 CENSUS TRACTS IN BOSTON dataset, which contains the geographical boundaries of each census tract in Boston.
- WICKED FREE WIFI LOCATIONS dataset, which contains the geographical location of each free WiFi location in Boston.

**Both datasets can be found in their respective folders in the repository.**

## Libraries Used

- geopandas
- pandas
- matplotlib
- seaborn


## Notebook Contents

1. **Getting Started**
- Packages like GeoPandas, Pandas, Matplotlib and Seaborn are imported to handle, analyze, and visualize the data.

2. **What is a shapefile**
- Data from `.shp` files are read in, which are essential for geospatial analysis.
- Explanations of why they are important and how to work with them

3. **Data Cleaning**
- Removing unnecessary columns and null values, for a smoother analysis process.

4. **Geospatial Analysis**
- Coordinate Reference Systems (CRS).
- Overlaying WiFi locations on top of the map of Boston.
- How to create a choropleth.
- Performing spatial joins, and more.

5. **Conclusions**
Inferences are made based on the visual and analytical examination of the data. Detailed insights are derived through thorough exploration of the geospatial relationships within the data.


## Instructions

1. Clone this repository or download `geo_eda.ipynb` and the data.
2. Make sure you have the necessary libraries installed.
3. Open and run the Jupyter Notebook to perform the geospatial analysis.
