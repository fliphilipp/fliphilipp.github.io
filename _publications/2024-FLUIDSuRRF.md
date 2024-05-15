---
title: "A Framework for Automated Supraglacial Lake Detection and Depth Retrieval in ICESat-2 Photon Data Across the Greenland and Antarctic Ice Sheets"
collection: publications
permalink: /publication/2024-FLUIDSuRRF
excerpt: 'In this paper, we present the Flat Lake and Underlying Ice Detection (FLUID) and Surface Removal and Robust Fit (SuRFF) algorithms which together provide a fully automated and scalable method for lake detection and depth determination from ICESat-2 ATL03 data, and establish a framework for its large-scale implementation using distributed high-throughput computing. We report FLUID/SuRFF algorithm performance over two regions known to have significant surface melt -- Central West Greenland and Amery Ice Shelf catchment in East Antarctica -- during two melt seasons. FLUID/SuRFF reveals a total of 1249 lakes up to 25 m deep, with more water during higher melt years.'
date: 2024-04-03
venue: 'Preprint under review for The Cryosphere Discussions'
paperurl: 'https://doi.org/10.5194/egusphere-2024-1156'
citation: 'Arndt, P. S. and Fricker, H. A.: A Framework for Automated Supraglacial Lake Detection and Depth Retrieval in ICESat-2 Photon Data Across the Greenland and Antarctic Ice Sheets, EGUsphere [preprint], 2024.'
og_image: FLUIDSuRRF-result-maps.jpg
---

**Abstract:** Supraglacial lakes on the ice sheets have been linked to ice shelf collapse in Antarctica and accelerated flow of grounded ice in Greenland. However, it is difficult to quantify the impact of supraglacial lakes on ice dynamics accurately enough to predict their contribution to future mass loss because large-scale assessments of meltwater volumes rely on models that are poorly constrained due to a lack of accurate depth measurements. Various recent case studies have demonstrated that accurate supraglacial lake depths can be obtained from ICESat-2’s ATL03 photon-level data product. However, ATL03 comprises hundreds of terabytes of unstructured point cloud data, which has made it challenging to use this bathymetric capability at scale. Here, we present the Flat Lake and Underlying Ice Detection (FLUID) and Surface Removal and Robust Fit (SuRFF) algorithms which together provide a fully automated and scalable method for lake detection and depth determination from ICESat-2 ATL03 data, and establish a framework for its large-scale implementation using distributed high-throughput computing. We report FLUID/SuRFF algorithm performance over two regions known to have significant surface melt -- Central West Greenland and Amery Ice Shelf catchment in East Antarctica -- during two melt seasons. FLUID/SuRFF reveals a total of 1249 lakes up to 25 m deep, with more water during higher melt years. In absence of ground truth data, manual annotation of test data suggests that our method reliably detects melt lakes whenever a bathymetric signal is discernible, and estimates water depths with a mean absolute error of 0.28 m. These results imply that our proposed framework has the potential to generate a comprehensive data product of accurate meltwater depths across both ice sheets.

## Links, data and code:
- Link to the discussion: [https://doi.org/10.5194/egusphere-2024-1156](https://doi.org/10.5194/egusphere-2024-1156)
- [Preprint PDF](https://egusphere.copernicus.org/preprints/2024/egusphere-2024-1156/egusphere-2024-1156.pdf)
- [Data set](https://zenodo.org/doi/10.5281/zenodo.10901737) for all detected lakes, with depths and imagery plots
- Source code:
  - [Zenodo](https://zenodo.org/doi/10.5281/zenodo.10905941)
  - [GitHub](https://github.com/fliphilipp/FLUIDSuRRF-code)
- Data and code for figure reproduction:
  - [Zenodo](https://zenodo.org/doi/10.5281/zenodo.10901826)
  - [GitHub](https://github.com/fliphilipp/FLUIDSuRRF-figures)
 
---

## Some figures of the main results

(all figures are in the README of [this GitHub repo](https://github.com/fliphilipp/FLUIDSuRRF-figures).)

![results for the Central West Greenland drainage basin](https://github.com/fliphilipp/images/blob/main/fig09-results_greenland_cw.jpg?raw=true)
Center maps: FLUID/SURFF algorithm testing in Greenland. Locations of melt lakes detected in ATL03 data for the Greenland Ice Sheet's Central West drainage basin for melt seasons 2019 and 2020, mapped over the corresponding seasons' maximum meltwater extent from Landsat 8. a)-j): Examples showing the underlying ATL03 photon clouds and water depths calculated by SuRRF, for some of the lakes shown on the maps. Numbers in lower right of panels are SuRFF lake quality scores.

![results for the Amery Ice Shelf catchment](https://github.com/fliphilipp/images/blob/main/fig10-results_amery.jpg?raw=true)
Center maps: FLUID/SuRFF algorithm testing in Antarctica. Locations of melt lakes that FLUID detected in ATL03 data for the Antarctic Ice Sheet's B-C drainage basin for melt seasons 2019-20 and 2020-21, mapped over the corresponding seasons' maximum meltwater extent from Landsat 8. Panels a-j: Examples showing the underlying ATL03 photon clouds and water depths calculated by SuRRF, for some of the lakes shown on the maps. Numbers in lower right of panels are SuRFF lake quality scores.
