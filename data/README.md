This folder contains all datasets used in this study. 

This is the location where the `zenodo-data` folder needs to be placed once it is downloaded from zenodo onto your local computer. 

1. Contents 
 - `/zenodo-data`: this folder will not exist when you initially clone the repository, navigate to [link] and download the folder and place it here in order to run the rest of the code. It is important to do this first thing or code will not run due to files not exisiting. 
    - **zenodo-data files breakdown**

 - `/landsat-yearly/`: this folder contains the yearly water history for the Colorado River Basin from 2015 - 2021. 
    - Each file contains classifications for surface water, 1: not water, 2: seasonal water, 3: permanent water, 4: no observation. 

- `/shapefiles/`: this folder contains all needed shapefiles to visualize geographic locations. Note that associated files are essential (ie. `.cpg`, `.dbf`, `.prj`, and `.shx`) even though the code only references the `.shp` file.
