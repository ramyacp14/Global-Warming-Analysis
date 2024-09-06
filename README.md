# Global Temperature Analysis Project

## Overview
This project conducts a comprehensive analysis of global temperature data to identify and visualize climate change trends. It leverages various data visualization techniques and geospatial analysis to present findings from different geographical perspectives.

## Key Analyses Performed
1. Global Temperature Trend Analysis
   - Examined long-term temperature changes using GlobalTemperatures.csv
   - Created time series visualizations to illustrate global warming trends

2. Country-wise Average Temperature Calculation
   - Calculated and visualized average temperatures for countries worldwide
   - Used choropleth maps to display global temperature distribution

3. Seasonal Temperature Analysis
   - Analyzed temperature variations across different seasons
   - Created visualizations to show seasonal patterns in various regions

4. US State Temperature Heatmap
   - Developed a heatmap visualization for temperature distribution across US states
   - Utilized geospatial libraries to map temperature data to state boundaries

5. Indian Cities Temperature Analysis
   - Focused on temperature trends in major Indian cities
   - Created city-specific visualizations and comparisons

## Geospatial Analysis
- Utilized geospatial libraries (folium, OpenCage Geocoder) for mapping and geographical data processing
- Created interactive maps to visualize temperature data on geographical layouts
- Implemented heat maps and choropleth maps for spatial temperature distribution

## Dependencies
- Data Processing: numpy, pandas
- Visualization: matplotlib, plotly, seaborn
- Geospatial Analysis: folium, opencage

## Data Sources
- GlobalLandTemperaturesByCountry.csv
- GlobalLandTemperaturesByState.csv
- GlobalLandTemperaturesByCity.csv
- GlobalTemperatures.csv

## Setup and Usage
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Ensure data files are in the project directory
4. Run the Jupyter notebook or Python script

## Visualizations
- Interactive charts and graphs using Plotly
- Geospatial visualizations with Folium:
  - World map with country-level temperature data
  - US map with state-level temperature heatmap
  - Indian map with city-specific temperature data
