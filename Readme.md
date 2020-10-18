[![DOI](https://zenodo.org/badge/305130504.svg)](https://zenodo.org/badge/latestdoi/305130504)

IR data extract
================

A python notebook allowing to extract the raw data embedded in FLIR R-jpegs metadata tags and saving it as .tiff files. The data is read as if transmissivity of the atmosphere was 1 (transparent) and the emissivity of the objects was 1 (black body). This allows the used to read the data and apply corrections individually for each pixel.

# Dependencies

The following python packages are required to read the FLIR files:

  - Exiftool (https://exiftool.org/)
  - Numpy
  - Tifffile
  - Math
  - Matplotlib
  - PIL

# How to Cite

Jonathan D. Muller, Lior Segev. (18 October 2020). IR-data-extract: Tool to extract FLIR raw data. DOI: 10.5281/zenodo.4104314  (URL:
<https://zenodo.org/record/4104314>), Python notebook

[![DOI](https://zenodo.org/badge/305130504.svg)](https://zenodo.org/badge/latestdoi/305130504)

# License

This software is distributed under the GPL version 3

# Acknowledgements

Based on the extensively researched R script 'Thermimage': [https://github.com/gtatters/Thermimage/](https://github.com/gtatters/Thermimage/)
