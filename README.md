# GPlately Documentation
A comprehensive collection of tutorials and documentation for [GPlately](https://gplates.github.io/gplately/latest/sphinx/html/index.html), a Python library for working with plate tectonic reconstructions and geospatial data analysis.

## Overview
This repository contains educational materials and tutorials to help users learn and effectively use GPlately for plate tectonic modeling, geological reconstructions, and geospatial data visualization.

## Getting Started

To run these notebooks locally:

Clone this repository:

```
git clone https://github.com/[username]/GPlately-basics.git
cd GPlately-basics
```

## Repository Structure

```
gplately-documentation/
├── tutorials/
│   └── basics/
    ├── 01a-load-plate-model-using-local-files.ipynb
    ├── 01a-load-plate-model-via-platemodelmanager.ipynb
    ├── 02a-load-and-plot-plate-model.ipynb
    ├── 02b-plot-plate-model-using-pygmt.ipynb
    ├── 03a–03d-load-and-plot-various-data-formats.ipynb
    ├── 04a–04c-load-and-reconstruct-raster.ipynb
└── data/
```

## Tutorials

### Basics Series
The basics tutorial series provides a comprehensive introduction to GPlately's core functionality for beginners:

1. Loading Data (01*.ipynb)

    - Loading plate reconstruction files from local files
    - Using the PlateModelManager for accessing remote datasets


2. Plotting and Visualization (02*.ipynb)

    - Visualizing reconstructed geological features
    - Plotting reconstructed coastlines through time
    - Working with PyGMT


3. Working with Data Files (03a–03d)
    - Load and visualize various geospatial data formats including CSV, XY, Shapefile, and GPML files


4. Raster Data Workflows (04*.ipynb)

    - Downloading raster datasets
    - Plotting and visualizing raster data
    - Reconstructing rasters through geological time