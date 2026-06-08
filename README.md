installation link: https://faun.rc.fas.harvard.edu/eschlafly/2dmap/map.html

This project utilizes the FITS file provided from the following website. It is a map of dust reddening from Pan-STARRS1. The data is derived from the stellar locus of 500 million stars observed by the survey. 

The installation was downloaded by running: python3 -m pip install dustmaps.

--
Descriptions:
- Map Code: the 2d code used to print out the design of the dustmap.
- Dust Reddening Map Table: reads the FITS file of the provided map and creates a title of different magnitudes and bands.
- Magnitude Correction Calculation: code used to calculation the correction of the magnitude (brightness without dust).
