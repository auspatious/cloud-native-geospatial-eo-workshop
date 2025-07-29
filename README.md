# Cloud Native Geospatial for Earth Observation Workshop

This repository contains workshop materials to that introduce
cloud native methods of working with Earth observation data products.

There are two activities, each with an annotated notebook:

- Activity 1: Find, Load and Visualise Sentinel-2 from Earth Search
- Activity 2: Cloud Native Land Productivity for SDG 15 using Landsat from MSPC
- Activity 3: Exploring Sea Surface Temperature Data using STAC Geoparquet

Activity 1 demonstrates how to query the Earth Search STAC API from Element-84
and produce a visually appealing image for a location in Utah. 

Activity 2 demonstrates how to measure land productivity
as a subindicator of Sustainable Development Goal indicator 15.3.1:
Proportion of land that is degraded over total land area. For more information
please see the
[Satellite Data Requirements for SDGIndicator 15.3.1](https://ceos.org/sdg/files/supportsheets/SDG_15.3.1_EO_Satellite_Data_Requirements_31Aug2022.pdf)
document.
The use case covers an area of agriculture and forest on the Ba River in Fiji.

Activity 3 demonstrates the use of a range of cloud native tools, including
the use of STAC Geoparquet as a store of STAC Items.

## Quickstart

### Tutorial PDF

Along with a completed notebook, we provide a [step-by-step PDF document](https://drive.google.com/file/d/1ysBCMfPq4Fc31w_Mwthoc6usUQiAV8c-/view?usp=sharing).
This was used to run the tutorial at the 2025 IGARSS in Brisbane, Australia.

### Start the Codespace

The easiest way to get started running through this workshop is to
launch a GitHub Codespace, which includes a VS Code web environment that
includes the ability to run and edit Jupyter Notebooks.

1. Click the green Code button
2. Click the Codespaces tab
3. Click Create codespace on main

![The required buttons for launching a Codespace](images/launch_codespace.png "Tabs for launching a Codespace in this Repository")

### Run the demonstration notebooks

Open the `Find_Load_Visualise.ipynb`
notebook and work through the cells.

Open the `Cloud_Native_Land_Productivity_For_SDG15.ipynb`
notebook and work through the cells.

Open the `03_Sea_Surface_Temperature_Timeseries_STAC_Geoparquet.ipynb`
notebook and work through the cells.

## Authorship and sponsorship

These notebooks were written by Alex Leith and Caitlin Adams, with
financial support from the
[Committee on Earth Observation Satellites](https://ceos.org/)
and advice from members of the [GEO Land Degradation Neutrality Flagship](https://geo-ldn.org/).

The notebooks were reviewed by Lavender Liu and Matthew Ellis.

## Further resources

### Earth Search STAC API from Element-84

* STAC catalog URL: [https://earth-search.aws.element84.com/v1/](https://earth-search.aws.element84.com/v1/)

### STAC API from Microsoft Planetary Computer

* STAC catalog URL: [https://planetarycomputer.microsoft.com/api/stac/v1/](https://planetarycomputer.microsoft.com/api/stac/v1/)

### STAC Geoparquet from the Australian Antarctic Division, hosted by Source Cooperative

* Documentation: [https://source.coop/repositories/ausantarctic/ghrsst-mur-v2/description](https://source.coop/repositories/ausantarctic/ghrsst-mur-v2/description)
* Geoparquet URL: [https://data.source.coop/ausantarctic/ghrsst-mur-v2/ghrsst-mur-v2.parquet](https://data.source.coop/ausantarctic/ghrsst-mur-v2/ghrsst-mur-v2.parquet)

### SDG indicator 15.3.1

There are multiple valuable resources related to measurment of land degredation through SDG indicator 15.3.1:

* [Good practice guidance. SDG indicator 15.3.1, Proportion of land that is degraded over total land area. Version 2.0.](https://www.unccd.int/resources/manuals-and-guides/good-practice-guidance-sdg-indicator-1531-proportion-land-degraded)
* [Satellite Data Requirements for SDGIndicator 15.3.1](https://ceos.org/sdg/files/supportsheets/SDG_15.3.1_EO_Satellite_Data_Requirements_31Aug2022.pdf)
* [TRENDS.EARTH: tracking land change](https://maps.trends.earth/map?tab=layers&zoom=7&center=lat%3D-8.477805461808186%26lng%3D-67.87353515625001&layers=%5B%5D&basemap=satellite)
