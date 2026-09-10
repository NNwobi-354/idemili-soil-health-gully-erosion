# Quantitative Evaluation of Gully Erosion Impacts on Soil Quality in the Idemili Drainage Area, Anambra State, Nigeria

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NNwobi-354/idemili-soil-health-gully-erosion/blob/main/Idemili_Soil_Health_Gully_Vulnerability_Analysis.ipynb)

This repository contains the dataset, computational scripts, and geographical boundary files supporting the research paper on soil quality degradation gradients surrounding active gully systems in the Idemili Drainage Area, Anambra State, Nigeria.

---

## Quick Start (Run Online)

Click the badge above or click here to **[Open the Analysis Notebook directly in Google Colab](https://colab.research.google.com/github/NNwobi-354/idemili-soil-health-gully-erosion/blob/main/Idemili_Soil_Health_Gully_Vulnerability_Analysis.ipynb)** to interactively run, inspect, and reproduce the statistical pipeline without installing dependencies locally.

---

## Repository Overview

This project provides a fully reproducible computational pipeline for multivariate indicator selection, non-linear sigmoidal scoring function calibration, and Soil Quality Index (SQI) modeling across lateral distance buffer zones relative to gully margins.

### Repository Structure

```text
├── README.md                                        # Project overview and documentation
├── Idemili_Soil_Health_Gully_Vulnerability_Analysis.ipynb # Main Jupyter Notebook containing complete analysis
└── data/
    ├── cleaned_idemili_soil_data.csv                # Preprocessed soil laboratory dataset for statistical analysis
    └── shapefile/                                   # Spatial boundary layers for the Idemili Drainage Area
        ├── Idemili_Drainage_Area.shp
        ├── Idemili_Drainage_Area.shx
        ├── Idemili_Drainage_Area.dbf
        └── Idemili_Drainage_Area.prj
