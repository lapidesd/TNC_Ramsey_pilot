# Data and Code Supplement for "Challenges in leveraging remote sensing and machine learning to improve spatiotemporal resolution of wet/dry mapping"

[![DOI](https://zenodo.org/badge/1302096082.svg)](https://doi.org/10.5281/zenodo.21399762)

This directory contains the code and data (except for raw PlanetScope imagery) needed to reproduce the results of this study. The contents of this directory are as follows:

* Code:
  * Ramsey_survey_imagery.ipynb: jupyter notebook matching field survey dates to cloud-free, clear-sky PlanetScope imagery dates
  * Ramsey_training_final.ipynb: jupyter notebook in which random forest models are trained, trimmed, and results visualized
  * Ramsey_wetted_channel_random_forest_preparation.ipynb: jupyter notebook cleaning and developing training data for the random forest models
  * imagery_dates_explore.ipynb: jupyter notebook demonstrating availability of PlanetScope Imagery and survey data for training
* Data:
  * Apr1.csv: csv of training data from new walking survey
  * DrainageLines.shp: shapefile of the geomorphic channel network at Ramsey Canyon
  * RamseyHydroData.csv: csv file containing precipitation and streamflow data for Ramsey Canyon
  * RamseyImageryDates.csv: csv file of available clear-sky PlanetScope Imagery obtained during the pilot period
  * RamseySurveyDates.csv: csv file of walking survey dates
  * Ramsey_surveyData.csv: csv of survey data from Ramsey Canyon
  * Surveyed_Ramsey_1999_2023.shp: shapefile containing reaches mapped for surface water presence during each annual survey
  * Wet_Ramsey_1999_2023.shp: shapefile containing reaches mapped as wet during each annual survey
  * daymet_precip.csv: csv file containing Daymet precipitation data for Ramsey Canyon
  * new_surveys_dry.shp: shapefile of dry reaches from non-June surveys
  * new_surveys_wet.shp: shapefile of wet reaches from non-June surveys
  * processed_with_dates_and_assumptions_fehmida.csv: csv file of training data snapped to geomorphic channel network and extended using assumed wet and assumed dry logic

