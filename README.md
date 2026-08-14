# Cloud Native Geospatial for Earth Observation Workshop

This repository contains workshop materials introducing cloud native geospatial
tools, technologies and concepts in relation to working with Earth observation data products.

There are four activities, each with an annotated notebook:

- [Activity 1: Find, Load and Visualise Sentinel-2 from Earth Search](01_Find_Load_Visualise.ipynb)
- [Activity 2: Cloud Native Land Productivity for SDG 15 using Landsat from MSPC](02_Cloud_Native_Land_Productivity_For_SDG15_LS.ipynb)
- [Activity 3: Exploring Sea Surface Temperature Data using STAC Geoparquet](03_Sea_Surface_Temperature_Timeseries_STAC_Geoparquet.ipynb)
- [Activity 4: Alpha Earth Embeddings](04_Alpha_Earth_Embeddings.ipynb)

Activity 1 demonstrates how to query the Earth Search STAC API from Element-84
and produce a visually appealing image for a location in Utah.

Activity 2 demonstrates how to measure land productivity as a subindicator of
Sustainable Development Goal indicator 15.3.1: Proportion of land that is
degraded over total land area. For more information please see the
[Satellite Data Requirements for SDG Indicator 15.3.1](https://ceos.org/sdg/files/supportsheets/SDG_15.3.1_EO_Satellite_Data_Requirements_31Aug2022.pdf).
The use case covers an area of agriculture and forest on the Ba River in Fiji.

Activity 3 demonstrates the use of a range of cloud native tools, including
STAC Geoparquet as a store of STAC Items.

Activity 4 demonstrates the use of Alpha Earth Embeddings for land cover classification.

## Quickstart

### Tutorial PDF

Along with completed notebooks, we provide a [step-by-step PDF document](https://drive.google.com/file/d/1rfjvJXh01oNO_Q_VmFkyEuOvG4yLMwGe/view?usp=sharing).

### GitHub Codespace

The easiest way to get started is to launch a GitHub Codespace, which provides
a VS Code environment with Jupyter Notebook support.

1. Click the green Code button
2. Click the Codespaces tab
3. Click Create codespace on main

![The required buttons for launching a Codespace](images/launch_codespace.png "Tabs for launching a Codespace in this Repository")

### Local development

Requires [uv](https://docs.astral.sh/uv/getting-started/installation/).

```bash
git clone https://github.com/auspatious/cloud-native-geospatial-eo-workshop.git
cd cloud-native-geospatial-eo-workshop
uv run --with jupyter jupyter lab
```

## Authorship and sponsorship

These notebooks were written by @caitlinadams, @alexgleith and @willjnz with financial
support from the [Committee on Earth Observation Satellites](https://ceos.org/)
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

### Alpha Earth Embeddings from TGE Labs, hosted by Source Cooperative

* Dataset: [https://source.coop/tge-labs/aef](https://source.coop/tge-labs/aef)

### SDG indicator 15.3.1

* [Good practice guidance. SDG indicator 15.3.1, Proportion of land that is degraded over total land area. Version 2.0.](https://www.unccd.int/resources/manuals-and-guides/good-practice-guidance-sdg-indicator-1531-proportion-land-degraded)
* [Satellite Data Requirements for SDG Indicator 15.3.1](https://ceos.org/sdg/files/supportsheets/SDG_15.3.1_EO_Satellite_Data_Requirements_31Aug2022.pdf)
* [TRENDS.EARTH: tracking land change](https://maps.trends.earth/map?tab=layers&zoom=7&center=lat%3D-8.477805461808186%26lng%3D-67.87353515625001&layers=%5B%5D&basemap=satellite)
