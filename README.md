# Bulgaria Before and After 1989

## Working title
Are the trends in selected demographic and health indicators statistically different between the communist period and the post-communist period?

## Project description
This project will examine whether selected demographic and health indicators in Bulgaria differ between the communist and post-communist periods. The analysis will focus on long-term trends, data cleaning and consolidation from at least two independent sources, exploratory data analysis, and statistical testing.

## Project workflow

The project uses two notebooks:
- `notebooks/01_data_inspection_and_cleaning.ipynb` for source inspection, cleaning, reshaping, and preparation
- `notebooks/02_final_project_analysis.ipynb` for the structured analytical presentation of the project

Cleaned intermediate tables are saved locally in `data/processed/` and then loaded into the final analysis notebook.


## Planned indicators
- Population
- Fertility rate or birth rate
- Infant mortality


## Current data sources
- World Bank - main long-run source currently used for demographic and health indicators from 1960 onward
- National Statistical Institute (NSI), Bulgaria - supplementary population data currently collected for the period 2001-2024
- Eurostat - supplementary population data currently collected for the period 2001-2023

## Data access

The data files used in this project are stored outside the GitHub repository.

To run the notebooks locally, download the data files from the external storage folder and place them in the following project directories:

- `data/raw/`
- `data/processed/`

The repository keeps the folder structure, but the actual data files are excluded from version control.

External data location:
[Google Drive folder](https://drive.google.com/drive/folders/1pXO6BvHH6eOApFvEkAB3KFogK9Dr0W85?usp=drive_link)


## Data folders

- `data/raw/` contains the original source files used for inspection and cleaning
- `data/processed/` contains cleaned intermediate tables generated during the workflow
