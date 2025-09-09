# Landsat and Sentinel Derived Surface Water Dataset Comparison in the Colorado River Basin

## Citation
By using this code or dataset in your research or projects, please cite the following publications: 
> *Puente, P. Condon, L.E., The Value of Increased Spatial Resolution for Inundated Area Mapping in the Western United States, GIScience and Remote Sensing, 2025 (in review)*

## Overview 
This repository contains the code, data, and resources supporting the work in the citation above. It provides tools for processing and analyzing the Landsat based [Global Surface Water Dataset](https://global-surface-water.appspot.com/) and Sentinel based [Dynamic World Global Surface Water](https://www.hydroshare.org/resource/9d60389f55b648149a788a2ff7bc3766/) for the Colorado River Basin. 

## Getting Started 
1. Clone this repository 

`git clone git@github.com:ppuentex/detection_comparison-CRB.git`

2. Download the data folder from Zenodo: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17042234.svg)](https://doi.org/10.5281/zenodo.17042234)

3. Unzip and place the `zenodo_data/` folder in the `detection_comparison-CRB/data` folder 

4. Navigate to the repository directory on the terminal:

`cd <your_local_folder>/detection_comparison-CRB` 

5. Create a new virtual environment: 

`python3 -m venv comp-env`

This will create a new folder `comp-env` in project directory. Make sure to add `/comp_env` into `.gitignore` file.

6. Set up the virtual environment. 

```
source surface-water-env/bin/activate #for macOS/Linex \
venv\Scripts\activate  #For Windows
```

7. Install dependencies. 
`pip install -r requirements.txt` 
This will download all dependencies and populate the virtual environment. 

