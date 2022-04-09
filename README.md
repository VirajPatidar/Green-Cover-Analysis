# Green-Cover-Analysis

_Analysis of geo mapped photographs and satellite imagery to estimate green cover over time across the globe._ <br/>
_A web app has also been developed using **Django REST Framework** and **React** for the same._

<br/>

**Link to the deployed ipynb notebooks:** [https://gcnotebooks.herokuapp.com/](https://gcnotebooks.herokuapp.com/) <br/> <br/>

### Web App: ###
**Link to the deployed web app:** [https://green-cover.netlify.app/](https://green-cover.netlify.app/) <br/>
**Link to frontend repo:** [https://github.com/VirajPatidar/green-cover-frontend](https://github.com/VirajPatidar/green-cover-frontend) <br/>
**Link to backend repo:** [https://github.com/VirajPatidar/green-cover-backend](https://github.com/VirajPatidar/green-cover-backend)

 <br/>
 
### Tech Stack: ###
**Vision Analytics, Machine Learning, Datasets and Satellite Imagery:**
* [Google Earth Engine Datasets](https://developers.google.com/earth-engine/datasets)
* [Google Earth Engine Python API](https://earthengine.google.com/)
* [Geemap](https://geemap.org/)  

<br/>

### Features: ###
* Rendering dynamic maps to analyse green cover and generate timelapses representing change in green cover.
* Time series chart/graph representing change in green cover over the years for the state of Maharashtra.
* Predicting type of landcover in the state of Maharashtra by performing supervised classification using existing datasets. 
* Analysis of air quality on basis of various parameters for the state of Maharashtra.

<br/>

### Features along with datasets used: ###

| TASK / FEATURE | DATASET |
| :---         | :---         
| Estimating Green Cover using Vegetation Indexes (Global)   | <ul><li> [USGS Landsat 8 Level 2, Collection 2, Tier 1](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C02_T1_L2) </li></ul>   |
| Timelapse for Normalized Difference Vegetation Index (NDVI) (Global)     | <ul><li> [USGS Landsat 8 Level 2, Collection 2, Tier 1](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C02_T1_L2) </li><li> [USGS Landsat 5 Level 2, Collection 2, Tier 1](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LT05_C02_T1_L2) </li></ul> |
| Time series graphical analysis representing Vegetation Indexes (NDVI & EVI) of Maharashtra     | <ul><li> [MOD13Q1.006 MODIS Terra Vegetation Indices 16-Day Global 250m](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MOD13Q1) </li></ul>     |
| Landcover Analysis of Maharashtra     | <ul><li> [USGS Landsat 8 Level 2, Collection 2, Tier 1](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C02_T1_L2) </li><li> [MCD12Q1.006 MODIS Land Cover Type Yearly Global 500m](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MCD12Q1) </li></ul>  |
| Analysing Air Quality of Maharashtra     | <ul><li> [Sentinel-5P NRTI AER AI: Near Real-Time UV Aerosol Index](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_AER_AI) </li><li> [Sentinel-5P NRTI CO: Near Real-Time Carbon Monoxide](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_CO) </li><li> [Sentinel-5P NRTI NO2: Near Real-Time Nitrogen Dioxide](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_NO2) </li><li> [Sentinel-5P NRTI HCHO: Near Real-Time Formaldehyde](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_HCHO) </li></ul>  |

<br/>
<br/>

