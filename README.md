# bikeshare_dataprep
Run this code to load and clean data for Toronto Bike Share analyses.

Key Features in Project
* API integration (both OpenData and Google Maps)
* Fuzzy matching 
* Data.table for efficient modifications to large dataframes
* sf and tmap packages for GIS objects/mapping

Dependencies
* RStudio

Installing
* Download the 2018 Bike Share Ridership data to a local directory. The files are in the data folder or available at the Toronto Open Data Catalogue (https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/)
* Download the 2019 Bike Share Ridership data to a local directory. The files are available at the Toronto Open Data Catalogue (https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/)

Executing 
* The opendatatoronto api is a bit glitchy. I tend to run the code chunks 1 to 10 one-by-one and then Run all chunks below. RStudo sometimes crashes if you "Run All Chunks" from chunk 1.
