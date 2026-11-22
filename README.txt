# SpaceX Falcon 9 Data Science Capstone — Public Dataset Reproduction

This package contains an independent reproduction using the public IBM Skills Network course dataset `dataset_part_2.csv`.

## Files
- `Data Science Capstone Project Report.pdf` — 16-page presentation/report.
- `Data_Science_Capstone_Project_Presentation.pptx` — editable PowerPoint source.
- `Capstone_Analysis_Tables.xlsx` — dataset and summary/model result tables.
- `public_spacex_dataset.csv` — 90-row historical course dataset used.
- `model_metrics.csv` — held-out model comparison.
- `sql_launch_site_results.csv`, `sql_orbit_results.csv` — executed SQLite summary outputs.
- PNG charts used in the presentation.

## Data source
https://raw.githubusercontent.com/Abhigyan-RA/SpaceX-capstone/main/dataset_part_2.csv

Dataset window: 2010-06-04 to 2020-11-05 (90 records).

## Reproducibility and limitations
The model comparison uses a stratified 80/20 train-test split (`random_state=2`) with four baseline classifiers. The held-out test set contains only 18 records, so metrics are highly variable and should not be treated as operational performance estimates. This is an independent reproduction and is not evidence of the student's own original notebooks, live Dash application, or GitHub repository. No personal GitHub URL is invented or inserted.
