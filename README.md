# SDS210 - Wildfire Mapping

Mapping of near real time satellite based fire detection in Australia. 

# Description
This project was undertaken for SDS210. The desired outputs were interactive maps plus a table showing fire detections from the last three hours and the closest fire station. This could hypothetically be used by fire managers to flag new fire detections and assign them to the nearest station for investigation. 

# Dependencies 
A list of dependencies for this project is as follows:

- Python 3.12 (miniconda and jupyter lab)
  - requests
  - pandas
  - geopandas
  - time
  - datetime
  - folium
  - numpy
  - branca

OS used was Windows 11.

GitHub Actions are used to rerun the notebook and refresh the data outputs every three hours.

# Installing
This project is available from this GitHub repo and can be downloaded and run as long as the required dependencies and data are available. All data paths are relative. 

It is recommended to set up a new environment if downloading and operating this program. 

# Data
Three main sources of data are used for this project.
#### FIRMS API
This API obtains the satellite fire detection data central to the project. For it to work, a MAP KEY (available from https://firms.modaps.eosdis.nasa.gov/api/map_key/) is required.

#### Australian LGA Data
Available here: https://www.abs.gov.au/statistics/standards/australian-statistical-geography-standard-asgs-edition-3/jul2021-jun2026/access-and-downloads/digital-boundary-files/LGA_2025_AUST_GDA2020.zip

#### Australian Rural Fire Service (RFS) station locations
Available from here: https://services.ga.gov.au/gis/rest/services/Emergency_Management_Facilities/MapServer/4

This is also available as an API if desired.

# Authors
Liam Edgeworth - liamjosephduffy.edgeworth@uzh.ch

# Version History
- 0.1 Initial Release    

# Acknowledgments
Hendrik Wulf and  for patient explanations and the code blocks used in SDS210 lessons. The FIRMS API Code Examples were very helpful to set up the API. AI was used to help with debugging and editing.


