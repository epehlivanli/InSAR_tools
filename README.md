# InSAR Tools

Utility scripts for InSAR-related visualization and export.

## Scripts

### `csv2kml.py`
Converts CSV-based geospatial displacement data into KML for visualization in 3D.

### `plot_displacement.py`
Plots displacement time series for one or two selected points from CSV input.

## Example usage

```bash

csv2kml.py --input file.csv --output file.kml --geometry-h5 inputs/geometryRadar.h5 --kml-name "Area of Interest Ascending/Descending 2022-2025" --vlim 1.0

plot_displacement.py --p1 349562 --f1 file1.csv --output point1displacement.png
