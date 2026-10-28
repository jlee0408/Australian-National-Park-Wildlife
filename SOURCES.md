# Sources and data notes

This document records the source families used by **Protected, But Not Everywhere**, the role of each source, the limitations that affect interpretation and their URL link. 
## Source inventory

|Source|Use in this project|Known interpretation notes|Links|
|-|-|-|-|
|Collaborative Australian Protected Areas Database (CAPAD), 2024|M1 protected-area records and locations; M3 protected-area locations|Records are database entries, not necessarily unique parks. Overlapping boundaries can inflate summed area. External territory records may not appear on the state map.|https://fed.dcceew.gov.au/datasets/ec356a872d8048459fe78fc80213dc70\_0/explore?location=-40.711703%2C115.622969%2C3<br />|
|IBRA 7.1 bioregion boundaries|M2 regional map and M3 region-to-location matching|Regional associations are not park-level species surveys.|https://fed.dcceew.gov.au/datasets/interim-biogeographic-regionalisation-for-australia-ibra-version-7-regions-states-and-territories/about<br /><br />|
|Australian terrestrial species-occurrence summaries|M2 occurrence/protection, threatened and introduced species summaries; regional input to M3|Occurrence records represent reported records, not total animal abundance. Summed periods may double-count species across periods.|https://researchdata.edu.au/aggregated-data-australian-1900-2022/2824305?|
|Threatened-species classifications|M3 threatened-species classification|Classification depends on the supplied threatened-status list and matching species names.|https://data.gov.au/data/dataset/threatened-species-state-lists|
|Land-cover data|C4 land-cover composition over time|A percentage share is compositional: a rise in one class changes the shares of other classes. Check unusual annual spikes against source documentation.|https://www.abs.gov.au/statistics/environment/environmental-accounts/national-land-cover-account/latest-release?|
|Natural woody vegetation data|C5 natural woody vegetation area by state/territory|Area alone does not establish vegetation condition or legal protection.|https://www.abs.gov.au/statistics/environment/environmental-accounts/national-land-cover-account/latest-release?|
|Threatened Species Index|C6 relative trends for monitored threatened species|The index is relative to its baseline and is not a census of every species or individual animal.|https://tsx.org.au/tsx2024/?type=all\&tgroup=All\&group=All\&subgroup=All\&state=All\&statusauth=Max\&status=NT\_VU\_EN\_CR\&management=All\&refyear=1985|
|Waterbird survey counts|C7 survey counts over time|Survey programs and effort differ; a one-off national survey can create a spike that should not be read as a population trend.|https://figshare.com/articles/dataset/UNSW\_Aerial\_Survey\_Waterbirds\_1983-2019\_1a\_csv/11853387/3?|
|Biodiversity monitoring-resource summaries|C8 data-source record counts and C9 regional monitoring records|Record volume measures reporting/monitoring activity, not abundance. C8 and C9 use different subsets and should not be compared as raw totals.|https://data.csiro.au/collection/csiro%3A64139v1|
|Exotic environmental pest assessments|C10 searchable pest risk profiles|Entry, establishment, spread and environmental-impact ratings are distinct assessment fields. An assessment is not proof of an outbreak or sighting.|https://www.agriculture.gov.au/abares/research-topics/invasive-species/national-priority-list-dataset?|

## 

