# Fossil Creek Post-Fire Vegetation Recovery (DAT 490 Capstone)

This repository contains the code, data processing workflow, and figures for my DAT 490 capstone project on post-fire vegetation recovery in the Fossil Creek watershed (Backbone Fire, 2021).

## Project Goal

Quantify vegetation change and recovery patterns after the Backbone Fire using satellite remote sensing and machine-learning models, and identify which environmental variables (slope, aspect, elevation, distance to streams, burn severity) best explain spatial variation in recovery.

## Repository Structure

- `EDA_FossilCreek.ipynb` – main exploratory data analysis notebook
- `Data 490 Capstone - Fossil Creek Study.ipynb` – project notebook tying together EDA and modeling plan
- `figs/` – exported figures used in the EDA report and rough draft (AOI map, fire overlay, NDVI/NBR histograms, dNBR histogram, NDVI change map)
- `data_raw/` – raw input datasets (not all are tracked in Git; large rasters and shapefiles are ignored)
- `data_processed/` – cleaned/derived rasters and tables used in analysis
- `docs/` – LaTeX reports (EDA report, rough draft, final paper – to be added)
- `.gitignore` – patterns for files/folders that should not be committed (large geospatial data, cache files, OS junk)

## Environment

Main tools and libraries:

- Python 3.x
- Jupyter Notebook
- `numpy`, `pandas`, `matplotlib`
- `rasterio`, `geopandas`, `shapely`
- `scikit-learn` (Decision Trees, Random Forests)

## How to Run

1. Create and activate a Python environment.
2. Install dependencies (with `pip install -r requirements.txt` once that file is added).
3. Open the notebooks in Jupyter and run cells in order.
