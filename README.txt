Brief Summary:

CANARC_*_loop

Code created to batch process daily sea ice concentration data from Univeristy of Bremen database (https://data.seaice.uni-bremen.de/). Based on code created with the support of CCR.

Input: 

1. Shape file as mask for delimiting desired area (Saved as .shp. See sea_ice_mask_qgis).
2. Location coordinates to anchor mask (Saved as point for mask location).
3. Params input (Year / Month / URL)

Output:

1. CSV file with daily mean SIC values (0-100) for desired area. 
2. Plot of daily mean SIC values for desired area.
3. Map for mask visualization, indicating selected pixels within radius/mask.
4. Map for mask visualization, indicating radius/mask selected within larger region. 



CANARC_GIF_sic

Will generate GIF from batch processed SIC data.
