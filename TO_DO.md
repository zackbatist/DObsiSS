DObsiSS
=======

**Notes / to do**

This is a list of changes and improvements that I hope to make in the future. 

- **DObsiSS.geojson**
  - [x] Re-order fields
  - [x] Remove json-ld info from top
  - [x] Add bounding box and CRS info to FeatureCollection key

- **DObsiSS.csv**
  - [x] Re-order fields

- **DObsiSS.jsonld**
  - [x] Separate info from geojson
  - [ ] Verify whether the schemas at the very top are necessary to include. Are they references to base indexes?
  - [ ] Research schema definitions for current blank entries
  - [ ] Look into the possibility of creating a new schema altogether, which can be displayed on another page [*]

- **Sources sub-directory**
  - [x] csv and geojson, with the same info in each
  - [ ] Possibly an independent json-ld base index for sources
  - [ ] Display links to info, chemical breakdowns and other resources for each entry on a new front-end page [*]

- **Bibliography**
  - [ ] Verify template, look into standard schemes/markups (bibjson, zotero, bibtex, etc)

- **Unpublished data**
  - [ ] Keep list of records 'on the radar' for upcoming release, and update 'notes' fields to reflect pending updates for applicable records already in the dataset
  - [ ] Make a submission form for easier data reporting [*]
  - [ ] Set up better rss feed / alert system

- **Chronological framework**
  - Main principle: flexibility
  - ASPRO will be used, but in a way that enables switching to other structures
  - [ ] Link this database with radiocarbon databases? Are there any out there that support LOD and that can be easily integrated? [*]
  - [ ] Once records have dates and ranges associated with them, it will be possible to create a visual timeline or time-sensitive map [*]

- **Front-end**
  - [ ] Make a submission form for easier data reporting [*]
  - [ ] Include more visualizations (d3, bloc.ks or just static highlights as well) [*]
  - [ ] Map interface that allows users to select/filter records / sources and visualize them in various ways (and also download a geojson file with those features!) - leaflet integration? Really just a browse and visualize function - not as extensive as ORBIS, but along similar lines [*]

[*]: More extensive work that would require more time to learn new skills and/or collaborate with others
