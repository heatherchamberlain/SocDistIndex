# SocDistIndex

Code to calculate mapped Ease of Social Distancing Index values within urban areas. 

The repository includes 2 Notebooks with code to create small spatial units and then calculate the index values, as follows:
- Notebook 1: Using data from OSM for features such as roads, rivers and railways, small spatial are created within each urban extent.
- Notebook 2: For theses spatial units, metrics on mean population density and space available around buildings are calculated. The index values are calculated from the subsequent built and population density scores.

Mapped outputs for 51 countries in sub-Saharan Africa are available to download from https://wopr.worldpop.org/?/SocialDistancing

This work is an output of the WorldPop Research Group (https://www.worldpop.org) at the University of Southampton, and has been developed as part of the GRID3 project (https://grid3.org). The DigitizeAfrica building footprints used in creating the output index for urban areas in sub-Saharan Africa are available for humanitarian purposes on request from Ecopia (https://www.ecopiatech.com/). Similar datasets for some countries are openly-available, such as Microsoft building footprints or Google Africa Open Buildings.

The code is written in Python (version 3.6.9), using ArcPy and has been tested with ArcGIS Pro version 2.5.1.
