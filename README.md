# Victoria Working Population Profile – Interactive Data Visualisation

This project is an interactive, multi-view data visualisation exploring the working population profile across all Local Government Areas (LGAs) in Victoria, Australia.
It brings together geospatial data, employment demographics, and interactive filtering to answer key questions about how employment varies by region, age, gender, and occupation.

The project was built using:
- R for large-scale data wrangling and preprocessing
- Vega/Vega-Lite for declarative visualisations
- JavaScript, HTML, and CSS for application logic and interaction

### Features

- **Employment by LGA (Choropleth Map):** Visualises employed population counts across all Victorian LGAs
- **Age distribution (stacked bar chart):** Shows employment counts by age bracket and employment category
- **Occupation breakdown (doughnut chart):** Visualises occupation distribution per LGA
- **Employment ratio visualisation (doughnut chart):** Displays employment/unemployment proportions
- **Unified Filtering System:** Custom JS system links a single search input to all Vega-Lite visualisations

### Data Sources

All datasets were sourced from the Australian Bureau of Statistics (ABS):
- [Working Population Profile (WPP) – 2021 Census DataPack](https://www.abs.gov.au/census/find-census-data/datapacks?release=2021&product=WPP&geography=ALL&header=S)
- [General Community Profile (GCP) – 2021 Census DataPack](https://www.abs.gov.au/census/find-census-data/datapacks?release=2021&product=GCP&geography=ALL&header=S)
- [ASGS Digital Boundary Files – Edition 3 (2021–2026)](https://www.abs.gov.au/statistics/standards/australian-statistical-geography-standard-asgs-edition-3/jul2021-jun2026/access-and-downloads/digital-boundary-files)
