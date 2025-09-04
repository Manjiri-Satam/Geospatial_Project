# Crime and Streetights in the UK : A Casestudy of Northern Ireland

### Introduction
Public street lighting is one of the most basic safety infrastructures. This project explores whether streetlight density relates meaningfully to the crimes reported in the UK, specifically in Northern Ireland. 
Using openly available data, we aim to understand whether certain less-lit areas are more vulnerable to crime. While there are several factors contributing to incidence of crime, identifying consistent spatial patterns could provide valuable insights for safer urban planning, including how such infrastructure must be distributed across different neighbourhoods.

### Research Question:
How does street lighting relate to where and what types of crime occur in Northern Ireland?

### Methodology
- We use publicly available crime and streetlight data, comprising 150,000+ geocoded crime incidents (April 2022 – March 2023) and approximately 250,000 streetlights in Northern Ireland.
- The streetlights were mapped and buffered at 30m radius.
- Crime incidents were spatially joined to these buffer zones to determine whether they fell within well-lit areas.
- We compared crime frequencies within and outside streetlight buffer zones.
- Spatial analysis was conducted using GIS tools to visualize patterns.
  
### Data Sources:
- Geocoded streetlight data from open data portals of local UK authorities ([https://data.gov.uk/](https://data.gov.uk/))
- UK Police Crime Data with monthly, geocoded, categorized crime incidents ([https://data.police.uk/data/](https://data.police.uk/data/))
- Police Station Boundaries from the same platform ([https://data.police.uk/data/boundaries/](https://data.police.uk/data/boundaries/))
