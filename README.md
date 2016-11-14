# general

For a general vision on what we are doing here, please read https://publicwiki.deltares.nl/display/OET/PostgreSQL+deployment+in+Azure.
In short, we want to assists data scientist in getting a Postgres-PostGIS database up-and-running in the shortest time possible. So they can spend their time on data collecting, data modelling, data analytics and data publication.

## Tasks / roles

### database
- postgresql-postgis
  - Maarten + Fedor
- pgadmin4
  - (depends on postgresql and reverse proxy)
  - Thijs

### web
- geoserver
  - Gerrit + Erna
- nginx
  - reverse proxy : https://github.com/openearth/stack/blob/master/playbook.yml nginx
  - Who?

### computing
- python
  - version 3.5 (or newest), with pyenv?
  - includes jupyter notebook 
