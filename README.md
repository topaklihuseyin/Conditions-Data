# Conditions Data
This page explains the use of global tags and the condition database with the CMS Open Data. All information was taken from [here](http://opendata.cern.ch/docs/cms-guide-for-condition-database).

A Global Tag is a coherent collection of records of additional data needed by the reconstruction and analysis software. 
The Global Tag is defined for each data-taking period, separately for collision and simulated data.

These records are stored in the condition database. Condition data include non-event-related information (Alignment, Calibration, Temperature, etc.) and parameters for the simulation/reconstruction/analysis software. For CMS Open Data, the condition data are provided as sqlite files in the `/cvmfs/cms-opendata-conddb.cern.ch/` directory, which is accessible through the CMS Open Data VM.

Most [physics objects](http://opendata.cern.ch/docs/cms-physics-objects-2011) such as `electrons`, `muons`, `photons` in the CMS Open Data are already calibrated and ready-to-use, and no additional corrections are needed other than selection and identification criteria, which will be applied in the analysis code. Therefore, simple analyses do not need to access the condition database. For example you can check [the Higgs analysis example](http://opendata.cern.ch/record/5500).

