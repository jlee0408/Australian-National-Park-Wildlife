# Protected, But Not Everywhere

A data visualisation exploring biodiversity, protected areas, wildlife observations and threatened species across Australia, built for Monash University's FIT3179 Data Visualisation 2 assignment.

Live Site : https://jlee0408.github.io/Australian-National-Park-Wildlife/



# What is this

This project explores how Australia's biodiversity is protected, how wildlife observations and threatened-species indicators have changed over time, and where important gaps remain in the available evidence.

Using data from Australian protected-area records, biodiversity and species-occurrence summaries, land-cover datasets, vegetation information, waterbird surveys and environmental pest assessments, the dashboard brings together maps and charts to tell a connected story about conservation across Australia.

The visualisation is presented as a single scrollable webpage, with interactive maps and charts built using Vega-Lite and Vega. It aims to make complex environmental data easier to explore while distinguishing recorded observations and relative indicators from direct measurements of wildlife abundance.

# Repository Structure

index.html is the live page

javascript.js controls the layout, typography, colours and responsive styling of the dashboard

style.css loads the datasets and chart specifications, renders the visualisations and manages interactive features.

specs/ contains the chart and map specifications as readable JSON files

data/ contains the source datasets, processed data and geographic boundary files required by the visualisations

DATA\_FILES\_REQUIRED.txt lists the datasets and geographic files expected by the project

FINDINGS\_AND\_DATA\_NOTES.txt summarises the main reported findings
SOURCES.md documents the data sources and their uses
NARRATIVE.md explains the story structure and the purpose of the individual visualisations
PALETTE.md documents the dashboard's colour palette and consistency guidelines

