# Open Street Map Fire Hydrant Exporter
Extract fire hydrants from open street map data

## Usage:

### Get OSM-Export

    curl "https://api.openstreetmap.org/api/0.6/map?bbox=7.749713,50.475351,7.795036,50.496703" > osm.xml

### Convert to csv

    ./OsmExport osm.xml > osm.csv
