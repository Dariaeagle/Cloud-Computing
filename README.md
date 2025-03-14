Sentinel-1 Backscatter Extraction using Google Earth Engine

Overview

This script processes Sentinel-1 SAR data to extract backscatter values (VH polarization) at specific station locations within a defined Region of Interest (ROI). The preprocessing and data extraction are conducted on the Google Earth Engine (GEE) platform, and the final results are exported as a CSV file for further analysis.

Preprocessing Reference

The preprocessing of Sentinel-1 SAR data was originally implemented using a script developed by the following authors:

Mullissa A., Vollrath A., Braun C., Slagter B., Balling J., Gou Y., Gorelick N., Reiche J.

The original JavaScript preprocessing script can be found here:

File: S1_ARD_TEST/wrapper.js

Version: v1.2

Date: 2021-04-01

GitHub Repository: https://github.com/adugnag/gee_s1_ard

Script Functionality

This script operates on preprocessed Sentinel-1 data and allows:

Filtering the dataset by orbit and platform.

Extracting backscatter values (VH polarization) at station locations.

Exporting the processed data as a CSV file to Google Drive for further analysis.

Usage Instructions

Running the Script in Google Earth Engine

Open the Google Earth Engine Code Editor.

Load the script from the following link:Run Script on GEE

Define your Region of Interest (ROI) and station locations.

Set the required filters for orbit, platform, and date range.

Run the script to extract backscatter values.

Export the results as a CSV file to Google Drive.

Output

The output file will be in CSV format and include:

Date

Station Code

Backscatter VH values

This CSV file can be further processed for analysis in Python, R, or any statistical software.

License

This project is open-source and follows the original licensing of the referenced preprocessing script.

Contact

For any questions or issues, please raise an issue on this GitHub repository or contact the script author.

Daria Ushakova
