## Capstone-Code-Portfolio-ATMS-596

This repository contains the data and code for my capstone project analyzing historical trends in Atmospheric Rivers (ARs) and their relationship to precipitation patterns along the U.S. West Coast. The research spans from 1950 to 2018, using the Gershunov AR Catalog and historical precipitation datasets to investigate changes in AR frequency, intensity, spatial distribution, and precipitation impacts over time.

Contents
- ARcatalog_NCEP_NEW_1948-2018_Comprehensive_FINAL_29JAN18.csv
- The Atmospheric River (AR) catalog containing variables such as AR ID, date, coastal latitude and longitude of landfall, integrated vapor transport (IVT), wind components, and more. This serves as the foundation for event identification.

Capstone_Project_Bourassa.ipynb
- A Jupyter Notebook that includes all code used for:

- Preprocessing the AR catalog
- Merging AR events with gridded precipitation data
- Performing trend analyses on AR frequency, intensity, and precipitation
- Identifying spatial shifts in AR landfall and precipitation centroids
- Comparing AR vs. non-AR precipitation and detecting trends in extreme AR-related rainfall
- Visualizing results with maps and time series

Requirements
To run the analysis, the following Python libraries are required:

- xarray
- pandas
- numpy
- matplotlib
- scipy
- pymannkendall (for trend significance testing)


