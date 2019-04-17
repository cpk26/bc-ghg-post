# Mapping Industrial Facility Greenhouse Gas Emissions in BC

This repository contains the data visualized in the blog post: [Mapping Industrial Facility Greenhouse Gas Emissions in BC](https://inletlabs.com/2019/01/20/BC_GHG.html).

The original files can be downloaded from the BC Government's website [here](https://www2.gov.bc.ca/gov/content/environment/climate-change/data/industrial-facility-ghg). This blog post visualizes the 2016 dataset, which was the latest at the time of posting. 

The excel spreadsheet (sites.xlsx) in this repository contains emissions data downloaded from the BC Government's website. It was manually reformatted to simplify loading into Python. Further processing is documented in the Jupyter Notebook: data_preprcoessing.ipynb 

The data was exported into a json file (sites.json), which was manually reformatted into a javascript array (sites.js) so that it can be easily displayed on a static site. The data is visualized in the blog post using [Leaflet.js](https://leafletjs.com/) and [D3.js](https://d3js.org/).