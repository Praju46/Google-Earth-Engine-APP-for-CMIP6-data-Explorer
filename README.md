# Google-Earth-Engine-APP-for-CMIP6-data-Explorer

# CMIP6 Climate Data Explorer 🌍

## Overview

The CMIP6 Climate Data Explorer is an interactive web application developed using Google Earth Engine (GEE) for visualizing global climate data. This tool allows users to explore climate projections, focusing on temperature and precipitation data from the CMIP6 models under different scenarios. Users can generate time series data by selecting areas of interest on the map and compare historical and future climate trends for various models and scenarios.

Try the App here:https://ee-prajaktamali1298.projects.earthengine.app/view/cmip6datatrend


## Features

- Visualize Historical and Future Climate Data: Explore temperature and precipitation trends from 1950 to 2100.
- Draw Polygons, Rectangles, or Select Points: Generate time series data by drawing shapes or selecting specific points on the map.
- Scenario Comparison: Switch between climate scenarios (e.g., SSP245, SSP585, Historical) for detailed analysis.
- Layered Map View: View different climate variables and customize visibility based on your analysis needs.
- Supports Various Models: Models include ACCESS-CM2 and MPI-ESM1-2-HR. (Note: Minimum and maximum temperature data are unavailable for IITM-ESM.)

## Data Sources

The app uses data from the NASA GDDP-CMIP6 dataset, including:
- Temperature: Minimum (tasmin) and Maximum (tasmax) temperature
- Precipitation: Precipitation rate (pr)

Explore more about the dataset on [NASA's EarthData website](https://earthdata.nasa.gov/).

## Usage Instructions

### 1. Clone this repository
bash
git clone https://github.com/your-repo-link.git


### 2. Open the App
Visit the deployed app here: CMIP6 Climate Data Explorer: https://ee-prajaktamali1298.projects.earthengine.app/view/cmip6datatrend

### 3. Interact with the UI:
- Select Climate Model: Choose the model (e.g., ACCESS-CM2, IITM-ESM) from the dropdown.
- Select Scenario: Pick the scenario (e.g., Historical, SSP245, SSP585).
- Select Year: Choose the year range for analysis (1950-2100).
- Draw Polygon/Rectangle or Select a Point: Generate time series data for your region of interest.


## Contributing

We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Add new feature'`).
4. Push the branch (`git push origin feature-branch`).
5. Submit a Pull Request.


## Contact

For questions, suggestions, or issues, please contact us at:
- Email: prajaktamali46@gmail.com
