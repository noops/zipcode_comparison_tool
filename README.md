# Zipcode Comparison Tool

### Resources
Software: VScode, Python, Jupyter Notebook
Libraries: Pandas, Plotly, MPU, uszipcode

## Overview
This is a jupyter notebook that allows the user to compare two zipcodes. Displays a map showing the user-inputted zipcodes, a bar graph comparing median income and median home value, summary statistics, and the distance between the two zipcodes. All Data comes from https://pypi.org/project/uszipcode/

## Map Screenshot
interactive map generated using Plotly. The distance shown below is calculated with the MPU library which uses the haversine formula that determines the great-circle distance between two points on a sphere given their longitudes and latitudes.
![my screenshot](/assets/img/zip_tool_shot.png)

## Bar Graph Screenshot
![my screenshot](/assets/img/zip_comp_shot.png)
