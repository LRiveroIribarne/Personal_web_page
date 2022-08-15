---
abstract: Vegetation biomass is a globally important climate-relevant terrestrial carbon pool and also drives local hydrological systems via evapotranspiration. Vegetation biomass of individual vegetation types has been successfully estimated from active and passive remote sensing data. However, for many tasks, landscape-level biomass maps across several vegetation types are more suitable than biomass maps of individual vegetation types. For example, the validation of ecohydrological models and carbon budgeting typically requires spatially continuous biomass estimates, independent from vegetation type. Studies that derive biomass estimates across multiple vegetation or land-cover types to merge them into a single landscape-level biomass map are still scarce, and corresponding workflows must be developed. Here, we present a workflow to derive biomass estimates on landscape-level for a large watershed in central Chile. Our workflow has three steps, First, we combine field plot-based biomass estimates with spectral and structural information collected from Sentinel-2, TanDEM-X and airborne LiDAR data to map grassland, shrubland, native forests and pine plantation biomass using random forest regressions with an automatic feature selection. Second, we predict all models to the entire landscape. Third, we derive a land-cover map including the four considered vegetation types. We then use this land-cover map to assign the correct vegetation type-specific biomass estimate to each pixel according to one of the four considered vegetation types. Using a single repeatable workflow, we obtained biomass predictions comparable to earlier studies focusing on only one of the four vegetation types (Spearman correlation between 0.80 and 0.84; normalized-RMSE below 16 % for all vegetation types). For all woody vegetation types, height metrics were amongst the selected predictors, while for grasslands, only Sentinel-2 bands were selected. The land-cover was also mapped with high accuracy (OA = 83.1 %). The final landscape-level biomass map spatially agrees well with the known biomass distribution patterns in the watershed. Progressing from vegetation-type specific maps towards landscape-level biomass maps is an essential step towards integrating remote-sensing based biomass estimates into models for water and carbon management.

author_notes:
- 
authors:
- Fabian Ewald Fassnacht
- Javiera Poblete-Olivares
- Lucas Rivero Iribarne
- Javier Lopatin
- Andrés Ceballos
- Mauricio Galleguillos
# date: "2013-07-01T00:00:00Z"
doi: ""
featured: true
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
projects:
- example
publication: In *International Journal of Applied Earth Observation and Geoinformation*
publication_short:
publication_types:
- "1"
publishDate: "2021-02-02T00:00:00Z"
slides: example
summary: Using Sentinel-2 and canopy height models to derive a landscape-level biomass map covering multiple vegetation types
tags: []
title: Using Sentinel-2 and canopy height models to derive a landscape-level biomass map covering multiple vegetation types
# url_code: ""
# url_dataset: ""
url_pdf: "https://www.researchgate.net/publication/344415275_Using_Sentinel-2_and_canopy_height_models_to_derive_a_landscape-level_biomass_map_covering_multiple_vegetation_types"
# url_poster: ""
# url_project: ""
# url_slides: ""
# url_source: ""
# url_video: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
