# Conditions Data
This page explains the use of global tags and the condition database with the CMS Open Data. All information was taken from [here](http://opendata.cern.ch/docs/cms-guide-for-condition-database).

A Global Tag is a coherent collection of records of additional data needed by the reconstruction and analysis software. 
The Global Tag is defined for each data-taking period, separately for collision and simulated data.

These records are stored in the condition database. Condition data include non-event-related information (Alignment, Calibration, Temperature, etc.) and parameters for the simulation/reconstruction/analysis software. For CMS Open Data, the condition data are provided as sqlite files in the `/cvmfs/cms-opendata-conddb.cern.ch/` directory, which is accessible through the CMS Open Data VM.
