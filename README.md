<img
  src="https://carbonplan-assets.s3.amazonaws.com/monogram/dark-small.png"
  height="48"
/>

# carbonplan / forest-offsets-paper

**jupyter notebooks that reproduce the figures from Badgely et al. (pending submission)**

[![GitHub][github-badge]][github]
[![Build Status]][actions]
![MIT License][]
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/carbonplan/retro-paper/main?urlpath=lab)

[github]: https://github.com/carbonplan/forest-offsets-paper
[github-badge]: https://badgen.net/badge/-/github?icon=github&label
[build status]: https://github.com/carbonplan/forest-offsets-paper/actions/workflows/main.yaml/badge.svg
[actions]: https://github.com/carbonplan/forest-offsets-paper/actions/workflows/main.yaml
[mit license]: https://badgen.net/badge/license/MIT/blue

For more information on this project, see the [carbonplan/forest-offsets](https://github.com/carbonplan/forest-offsets-paper) repository.

## data

Here we describe all of the datasets used in this project.

### primary sources

| Dataset                       | Description | Source                                                                                              | Format / Schema   |
| ----------------------------- | ----------- | --------------------------------------------------------------------------------------------------- | ----------------- |
| digitized ifm project records | TODO        | [link](https://carbonplan.blob.core.windows.net/carbonplan-retro/projects/retro-db-light-v1.0.json) | JSON ([schema]()) |

### results

| Dataset                          | Description | Source                                                                                                          | Format / Schema   |
| -------------------------------- | ----------- | --------------------------------------------------------------------------------------------------------------- | ----------------- |
| reclassification-crediting-error | TODO        | [link](https://carbonplan.blob.core.windows.net/carbonplan-retro/results/reclassification-crediting-error.json) | JSON ([schema]()) |
| prism-supersections              | TODO        | [link](https://carbonplan.blob.core.windows.net/carbonplan-retro/arbitrage/prism-supersections/79.json)         | JSON ([schema]()) |
| crediting-verification           | TODO        | [link](https://carbonplan.blob.core.windows.net/carbonplan-retro/results/crediting-verification.json)           | JSON ([schema]()) |
| common-practice-verification     | TODO        | [link](https://carbonplan.blob.core.windows.net/carbonplan-retro/results/common-practice-verification.json)     | JSON ([schema]()) |
| classifier_fscores               | TODO        | [link](https://carbonplan.blob.core.windows.net/carbonplan-retro/reclassification/classifier_fscores.json)      | JSON ([schema]()) |
| reclassification-labels          | TODO        | [link](https://carbonplan.blob.core.windows.net/carbonplan-retro/results/reclassification-labels.json)          | JSON ([schema]()) |

### gis layers

| Dataset                          | Description                                  | Source                                                                                                            | Format / Schema |
| -------------------------------- | -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | --------------- |
| ne_110m_admin_1_states_provinces | Natural Earth State and Province geometries. | [link](https://carbonplan.blob.core.windows.net/carbonplan-retro/ancillary/ne_110m_admin_1_states_provinces.json) | GeoJSON         |
| EcomapSections                   | USDA EcomapSections dataset.                 | [link](https://data.fs.usda.gov/geodata/edw/edw_resources/shp/S_USA.EcomapSections.zip)                           | ESRI Shapefile  |

## license

All the code in this repository is [MIT](https://choosealicense.com/licenses/mit/) licensed, but we request that you please provide attribution if reusing any of our digital content (graphics, logo, articles, etc.).

## about us

CarbonPlan is a non-profit organization that uses data and science for climate action. We aim to improve the transparency and scientific integrity of carbon removal and climate solutions through open data and tools. Find out more at [carbonplan.org](https://carbonplan.org/) or get in touch by [opening an issue](https://github.com/carbonplan/forest-offsets-paper/issues/new) or [sending us an email](mailto:hello@carbonplan.org).
