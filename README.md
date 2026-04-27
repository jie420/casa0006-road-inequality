# Is Road Accident Risk Socially and Spatially Unequal Across England?

A multi-method analysis of deprivation, urbanicity, and casualty severity 
using STATS19 road casualty data (2020–2024).

## Repository contents

- `Template_submission_CASA0006.ipynb` — Main analysis notebook
- `dft-road-casualty-statistics-collision-last-5-years.csv` — STATS19 collision data
- `dft-road-casualty-statistics-casualty-last-5-years.csv` — STATS19 casualty data
- `Indices_of_Deprivation-2025-data-download-file.../` — IMD 2025 data
- `Lower_layer_Super_Output_Areas_December_2...` — LSOA boundary GeoJSON
- `nomis_2026_04_20_045529.xlsx` — ONS population estimates

## How to run

All data is loaded remotely from this repository via `pd.read_csv()`. 
Clone or open the notebook directly in JupyterLab with SDS Docker.
