# GEO244
Materials for my GEO 244 Space Geodesy class

Included here are a series of Jupyter notebooks that make use of real GNSS and InSAR data:

## [00_set_up_environment](00_set_up_environment/)
Includes a conda YML file for an environment for the class, and instructions on how to use it.

## [01_download_earthscope_data](01_download_earthscope_data/)
A Jupyter notebook for setting up a SSO token for downloading data from EarthScope.

## [02_gnss_time_series_decomposition](02_gnss_time_series_decomposition/)
A Jupyter notebook demonstrating ways of decomposing a GNSS time series $-$ detrending, solving for offsets, solving for postseismic transients and removing seasonal signals.

## [03_gnss_preprocessing_and_processing](03_gnss_preprocessing_and_processing/)
How to convert data from 'raw' (proprietary binary) format to RINEX, how to estimate important metadata parameters, how to edit RINEX headers, and how to use the OPUS processing service to turn your data into positions.

## [04_insar_processing_with_isce](04_insar_processing_with_isce/)
A Jupyter notebook containing a very basic workflow to run topsApp.py on Sentinel-1 data downloaded from the Alaska Satellite Facility, including some in-notebook plotting options.

## [05_simple_time_series_analysis_with_mintpy](05_simple_time_series_analysis_with_mintpy/)
A Jupyter notebook designed to get you up and running with processed InSAR data from the Alaska Satellite Facility's cloude-based 'HyP3' processor in the MintPy software. 
