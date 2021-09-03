# PLAN

- `Community Districts` consist of `Subway Stations` that consist of `Crime Datapoints`

## Datasets

- Community Districts

  - [Community District Population Dataset](https://data.cityofnewyork.us/City-Government/New-York-City-Population-By-Community-Districts/xi7c-iiu2)
  - [Community District Geometry Area](https://data.cityofnewyork.us/City-Government/2010-Neighborhood-Tabulation-Areas-NTAs-/cpf4-rkhq)

- Subway Stations

  - [Subway Station Entrances](https://data.cityofnewyork.us/Transportation/Subway-Entrances/drex-xx56)
  - Create custom polygons from entrance points

- Crime Datapoints

  - YTD Crime Data from [Compstat](https://compstat.nypdonline.org/2e5c3f4b-85c1-4635-83c6-22b27fe7c75c/view/89) (Python Script already created)
  - [Historic Crime Data](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrests-Data-Historic-/8h9b-rp9u)

## Tech

- (Backend) [Starlette](https://www.starlette.io)
- (Database) MySQL
- (Search) ElasticSearch, [GeoShape Querying](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-geo-shape-query.html)
- (Frontend) React.js
