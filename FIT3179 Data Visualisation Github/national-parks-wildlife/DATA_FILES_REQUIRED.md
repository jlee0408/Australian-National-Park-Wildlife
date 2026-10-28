# Required runtime data files

The dashboard source code and JSON specifications are included in the project. The recovered project archive did not include the full original CSV datasets and geographic boundary files.

## M1 — Protected areas by state or territory

* `data/Collaborative\\\_Australian\\\_Protected\\\_Areas\\\_Database\\\_(CAPAD)\\\_2024\\\_-\\\_Terrestrial\\\_\\\_.csv`
* `data/geo/au\\\_states.topo.json`
* Fallback boundary file, if required: `data/geo/au\\\_states\\\_raw.geojson`

## M2 — Wildlife indicators by IBRA region

* `data/geo/IBRA7\\\_regions.geojson`
* Fallback boundary file, if required: `data/geo/ibra71\\\_regions.json`
* `data/SummaryData-ProtectionStatusAustralianTerrestrialSpeciesOccurrences-1.1.2023-06-13\\\_part\\\_1.csv`
* `data/SummaryData-ProtectionStatusAustralianTerrestrialSpeciesOccurrences-1.1.2023-06-13\\\_part\\\_2.csv`
* `data/SummaryData-ProtectionStatusAustralianTerrestrialSpeciesOccurrences-1.1.2023-06-13\\\_part\\\_3.csv`
* `data/SummaryData-ThreatenedSpeciesOccurrencesByTerrestrialEcoregion-1.1.2023-06-13.csv`
* `data/SummaryData-IntroducedSpeciesOccurrencesByTerrestrialEcoregion-1.1.2023-06-13.csv`

## M3 — Threatened species associated with protected-area locations

Uses the CAPAD file, IBRA boundary file and three protection-status CSV parts listed above, plus:

* `data/20260828spcs.csv`

## C4 — Land-cover composition

* `data/Proportion of land cover classes, Australia 1988–2024.csv`

## C5 — Natural woody vegetation by state or territory

* `data/Time series for Land Cover Stock Positions, states and territories, 1988 to 2024 (hectares).csv`

## C6 — Threatened Species Index

* `data/tsx-trend-dataset=tsx2024\\\&type=all\\\&tgroup=All\\\&group=Terrestrial\\\&subgroup=All\\\&state=All\\\&statusauth=Max\\\&status=NT\\\_VU\\\_EN\\\_CR\\\&management=All\\\&refyear=1985.csv`

## C7 — Waterbird aerial survey

* `data/UNSW Aerial Survey Waterbirds 1983-2019 1a.csv`

## C8 — Monitoring data sources

* `data/data\\\_sources\\\_env\\\_monitoring.csv`

## C9 — Monitoring effort by region

* `data/summary\\\_monitoring\\\_effort\\\_terrestrial.csv`

## C10 — Exotic environmental pest profiles

* `data/Date\\\_EexoticEnvironmentalPests\\\_v1.0.0.csv`

## 

