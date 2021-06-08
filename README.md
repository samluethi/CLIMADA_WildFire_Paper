# CLIMADA WildFire Paper
This repository contains a folder for the code used in a research article. The code replicates the figures and explains software components implemented in [CLIMADA Python](https://github.com/CLIMADA-project/climada_python).

Lüthi, S., Aznar-Siguan, G., Fairless, C., and Bresch, D. N.: Globally consistent assessment of economic impacts of wildfires (submitted)

The whole wildfire module, incl. calibrated impact functions, will be made available as part of CLIMADA with release [CLIMADA v.2.2.0+](https://github.com/CLIMADA-project/climada_python). 
Prior to that release the module can be found on the branch [wildfire-update](https://github.com/CLIMADA-project/climada_python/tree/wildfire-updated)

Contact: [Samuel Lüthi](mailto:samuel.luethi@usys.ethz.ch)

## Content:

#### Scripts
- Script for preparing wildfire and exposure data
- Script for calibration incl. cross validation
- Scribt to produce plots
- Jupyter notebook to reproduce the results of the two case studies displayed in the study (Australia 2020 and Chile 2017)

#### climada_python
- the two new file which will be added to the climada repository (they are still subject to code review prior to merging into the climada repository.
However, this will not impact any results)

#### data
- results of the calibration incl. cross validation
- damage estimates
- FIRMS data for the case studies

All other underlying data (information from EM-DAT, expoure and hazard data for the calibration) are available on request.

## Documentation:

Documentation for CLIMADA is available on Read the Docs:
* [online (recommended)](https://climada-python.readthedocs.io/en/stable/)
* [PDF file](https://buildmedia.readthedocs.org/media/pdf/climada-python/stable/climada-python.pdf)

-----
www.wcr.ethz.ch
