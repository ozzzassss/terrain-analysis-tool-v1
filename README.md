# Terrain Analysis & Policy Impact Tool (V1)

##  Project Overview
This repository contains a high-performance geospatial tool designed to analyze Digital Elevation Models (DEMs). It allows users to dynamically assess the impact of mountain height recognition policies by identifying terrain that exceeds specific elevation thresholds.


##  Key Features
* **Dynamic Thresholding:** Interactive slider interface to adjust elevation cutoffs in real-time.
* **Automated Impact Metrics:** Instant calculation of impacted land area (km²) and percentage coverage.
* **Geophysical Intelligence:** Built-in logic to interpret topographic relief and geomorphological character.
* **High-Contrast Visualization:** Professional "Plasma" heatmapping on a black baseline for clear data differentiation.
* **Big Data Optimized:** Implemented with memory-efficient decimated reads for handling large-scale raster datasets.

##  Technical Stack
* **Language:** Python 3
* **Geospatial Processing:** `rasterio` (GDAL-based), `numpy`
* **Data Visualization:** `matplotlib`, `ipywidgets`
* **Platform:** Google Colab / Jupyter Notebooks

##  How to Use
1.  Upload your `.tif` elevation data to your environment.
2.  Update the `filename` variable in the script to point to your data.
3.  Use the interactive slider to perform "What-If" analysis on different elevation policies.

---
*Developed for professional geospatial analysis and policy impact assessment.*
