This folder contains all datasets used in this study. 

This is the location where the `zenodo-data` folder needs to be placed once it is downloaded from zenodo onto your local computer. 

1. Contents 
 - `/zenodo-data`: this folder will not exist when you initially clone the repository, navigate to [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17042234.svg)](https://doi.org/10.5281/zenodo.17042234) and download the folder and place it here in order to run the rest of the code. It is important to do this first thing or code will not run due to files not exisiting. 
    - **zenodo-data files breakdown**

 - `/landsat-yearly/`: this folder contains the yearly water history for the Colorado River Basin from 2015 - 2021. 
    - Each file contains classifications for surface water, 1: not water, 2: seasonal water, 3: permanent water, 4: no observation. 

- `/shapefiles/`: this folder contains all needed shapefiles to visualize geographic locations. Note that associated files are essential (ie. `.cpg`, `.dbf`, `.prj`, and `.shx`) even though the code only references the `.shp` file.

   - `LCRB_statelines.shp`: This file has the Lower Basin HUC2 15, where it is partially cropped to stay within statelines. 
   - `UCRB_statelines.shp`: This file has the Upper Basin HUC2 14. 
   - `CRB_huc4.shp`: This file contains all HUC4s for the Upper (1401 - 1408) and Lower Basin (1501 - 1507) where HUC4 1507 is cropped to stay within statelines. 

- `crb_precip_pdsi.csv`: This file contains the yearly average precipitation and PDSI values for the years 2015 to 2023 for the Upper, Lower, and whole Colorado River Basin. 
