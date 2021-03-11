<img
  src="https://carbonplan-assets.s3.amazonaws.com/monogram/dark-small.png"
  height="48"
/>

# carbonplan / retro-paper

**jupyter notebooks that reproduce the figures from Badgely et al. (pending submission)**

[![GitHub][github-badge]][github]
[![Build Status]][actions]
![MIT License][]
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/carbonplan/retro-paper/main?urlpath=lab)

[github]: https://github.com/carbonplan/retro-paper
[github-badge]: https://badgen.net/badge/-/github?icon=github&label
[build status]: https://github.com/carbonplan/retro-paper/actions/workflows/main.yaml/badge.svg
[actions]: https://github.com/carbonplan/retro-paper/actions/workflows/main.yaml
[mit license]: https://badgen.net/badge/license/MIT/blue

For more information on this project, see the [carbonplan/retro](https://github.com/carbonplan/retro) repository.

## data

Here we describe all of the datasets used in this project.

### primary sources

#### digitized ifm project records

- Description: TODO
- Source: https://carbonplan.blob.core.windows.net/carbonplan-retro/projects/retro-db-light-v1.0.json
- Schema: JSON (link)

### results

#### reclassification-crediting-error

- Description: TODO
- Source: https://carbonplan.blob.core.windows.net/carbonplan-retro/results/reclassification-crediting-error.json
- Schema: JSON (link)

#### prism-supersections

- Description: TODO
- Source: https://carbonplan.blob.core.windows.net/carbonplan-retro/arbitrage/prism-supersections/79.json
- Schema: GeoJSON

#### crediting-verification

- Description: TODO
- Source: https://carbonplan.blob.core.windows.net/carbonplan-retro/results/crediting-verification.json
- Schema: JSON (link)

#### common-practice-verification

- Description: TODO
- Source: https://carbonplan.blob.core.windows.net/carbonplan-retro/results/common-practice-verification.json
- Schema: JSON (link)

#### classifier_fscores

- Description: TODO
- Source: https://carbonplan.blob.core.windows.net/carbonplan-retro/reclassification/classifier_fscores.json
- Schema: JSON (link)

#### reclassification-labels

- Description: TODO
- Source: https://carbonplan.blob.core.windows.net/carbonplan-retro/results/reclassification-labels.json
- Schema: JSON (link)

### gis layers

#### ne_110m_admin_1_states_provinces

- Description: Natural Earth State and Province geometries.
- Source: https://carbonplan.blob.core.windows.net/carbonplan-retro/ancillary/ne_110m_admin_1_states_provinces.json
- Schema: GeoJSON

#### S_USA.EcomapSections

- Description: USDA EcomapSections dataset.
- Source: https://data.fs.usda.gov/geodata/edw/edw_resources/shp/S_USA.EcomapSections.zip
- Schema: Shapefile

## license

All the code in this repository is [MIT](https://choosealicense.com/licenses/mit/) licensed, but we request that you please provide attribution if reusing any of our digital content (graphics, logo, articles, etc.).

## about us

CarbonPlan is a non-profit organization that uses data and science for climate action. We aim to improve the transparency and scientific integrity of carbon removal and climate solutions through open data and tools. Find out more at [carbonplan.org](https://carbonplan.org/) or get in touch by [opening an issue](https://github.com/carbonplan/retro-paper/issues/new) or [sending us an email](mailto:hello@carbonplan.org).
