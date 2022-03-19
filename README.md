#  Geopandas with dash

# conda

install:

1. geopandas
2. dash
3. dash-bootstrap-components
4. dash_core_components

conda activate dashgeopandas


## Docker build
docker build -t ploylygeojson .

## Docker run

# For linux
docker run --rm --name query -p 8050:8050 ploylygeojson 

