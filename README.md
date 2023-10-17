# Flood Grid Rescaler

[![DOI](https://zenodo.org/badge/547351392.svg)](https://zenodo.org/badge/latestdoi/547351392)

A QGIS Processing script for rescaling flood hazard rasters (water depth, water surface elevation, and DEM) that includes the following tools:
- Aggregation via Averaging: Two methods for coarsening flood hazard grids described in [Bryant et. al., (2022)]

The algorithms are tested against QGIS 3.28.11

## Installation Instructions
### download the scripts
download the algorithms of interest from the [processing folder](floodrescaler/processing) to your local machine

### add to your QGIS profile
In the QGIS [Processing Toolbox](https://docs.qgis.org/3.22/en/docs/user_manual/processing/toolbox.html#the-toolbox), select the python icon drop down ![Scripts](/assets/mIconPythonFile.png) , and `Add Script to Toolbox...`. This should load new algorithms to the `Scripts/FloodRescaling` group on the Processing Toolbox as shown below:

![screen capture](/assets/processingToolbox_screengrab.png)



## Use
Instructions are provided on the algorithm dialog

## Example Data

Example data is provided in the [examples](/examples) folder

## Development

create a virtual environment from the supported QGIS version and the `./requirements.txt` file. 
