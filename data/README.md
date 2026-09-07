# Data

This project uses publicly available healthcare wait-time data from the Canadian Institute for Health Information (CIHI).

## Data Source

The dataset used in this project is available from:

[CIHI — Explore wait times for priority procedures across Canada](https://www.cihi.ca/en/explore-wait-times-for-priority-procedures-across-canada)

The historical data tables include national, provincial, and regional wait-time data beginning in 2008.

On the CIHI page, navigate to **Additional resources → Data tables → Download data tables (XLSX)**.

## File Setup

The raw Excel file is not included in this repository.

After downloading the XLSX file, place it at:

`data/Raw Data/wait-times-priority-procedures-in-canada-2008-2025-data-tables-en.xlsx`

The analysis notebook expects this file path when loading the dataset.
