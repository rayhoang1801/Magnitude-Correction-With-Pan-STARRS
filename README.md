installation link: https://faun.rc.fas.harvard.edu/eschlafly/2dmap/map.html
The installation was downloaded by running: python3 -m pip install dustmaps.

This project utilizes the FITS file provided from the following website. It is a map of dust reddening from Pan-STARRS1. It is able to map the interstellar dust by the different surveys of dust reddening E(B-V) throughout the Milky Way. 

The purpose of the code helps render a full sky as a 2-dimensional Mollweide proection of the density distribution. It also computes intrinsic, true brighness for the provided objects that are obscured by the interstellar medium. 
--
Descriptions:
- Map Code: the 2d code used to print out the design of the dustmap.
- Dust Reddening Map Table: reads the FITS file of the provided map and creates a title of different magnitudes and bands.
- Magnitude Correction Calculation: code used to calculation the correction of the magnitude (brightness without dust).
