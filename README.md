# Sentinel-1 Backscatter Extraction using Google Earth Engine

## Overview
This script processes Sentinel-1 SAR data to extract backscatter values (VH polarization) at specific station locations within a defined Region of Interest (ROI). The preprocessing and data extraction are conducted on the Google Earth Engine (GEE) platform, and the final results are exported as a CSV file for further analysis.

## Preprocessing Reference
The preprocessing of Sentinel-1 SAR data was originally implemented using a script developed by the following authors:
- Mullissa A., Vollrath A., Braun C., Slagter B., Balling J., Gou Y., Gorelick N., Reiche J.

The original JavaScript preprocessing script can be found here:
- **File:** `S1_ARD_TEST/wrapper.js`
- **Version:** v1.2
- **Date:** 2021-04-01
- **GitHub Repository:** [https://github.com/adugnag/gee_s1_ard](https://github.com/adugnag/gee_s1_ard)

## Script Functionality
This script operates on preprocessed Sentinel-1 data and allows:
- Filtering the dataset by orbit and platform.
- Extracting backscatter values (VH polarization) at station locations.
- Exporting the processed data as a CSV file to Google Drive for further analysis.

## Usage Instructions
### Running the Script in Google Earth Engine
1. Open the Google Earth Engine Code Editor.
2. Load the script from the following link:  
   [Run Script on GEE]([https://code.earthengine.google.com/your_script_id_here](https://code.earthengine.google.com/6f3fe5ff1c04036bd7cd0d7530426ac7))
3. Define your Region of Interest (ROI) and station locations.
4. Set the required filters for orbit, platform, and date range.
5. Run the script to extract backscatter values.
6. Export the results as a CSV file to Google Drive.

## Output
The output file will be in CSV format and include:
- **Date**
- **Station Code**
- **Backscatter VH values**

This CSV file can be further processed for analysis in Python, R, or any statistical software.

## License
This project is open-source and follows the original licensing of the referenced preprocessing script.

## Contact
For any questions or issues, please raise an issue on this GitHub repository or contact the script author.

---
**Author:** Your Name  
**Date:** YYYY-MM-DD
