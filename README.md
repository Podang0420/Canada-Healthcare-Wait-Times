# Canadian Healthcare Wait Times Analysis (2008–2025)

## Project Overview

This project analyzes healthcare wait-time trends for priority medical procedures across Canadian provinces from 2008 to 2025.

The analysis focuses on four procedures:

- Cataract Surgery
- Hip Replacement
- Knee Replacement
- Radiation Therapy

Wait-time performance is evaluated using median (P50) wait times, 90th percentile (P90) wait times, benchmark achievement rates, and procedure volumes.

The project examines long-term trends, differences across procedures and provinces, and changes observed across the pre-COVID, pandemic, and recovery periods.

## Research Questions

1. How have wait times for priority medical procedures changed across Canadian provinces from 2008 to 2025?
2. Which procedures show the greatest deterioration or improvement in wait-time performance?
3. How did wait-time patterns differ between the pre-COVID (2008–2019), pandemic (2020–2022), and recovery (2023–2025) periods?

## Tools & Technologies

- Python
- pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook
- Excel / openpyxl

## Dataset

The analysis uses publicly available wait-time data from the Canadian Institute for Health Information (CIHI), covering priority medical procedures across Canadian provinces from 2008 to 2025.

The dataset includes:

- Median (P50) wait times
- 90th percentile (P90) wait times
- Percentage of procedures completed within benchmark
- Procedure volumes

The raw dataset is not included in this repository. Instructions for obtaining and organizing the data are provided in the `data/` directory.

## Methodology

The analysis was conducted in Python using pandas for data preparation and aggregation, Matplotlib for visualization, and SciPy for simple linear trend analysis.

The main analytical steps included:

1. Cleaning and filtering annual provincial data from 2008 to 2025.
2. Comparing P50 and P90 wait-time trends across four priority procedures.
3. Measuring changes in wait times and benchmark achievement between 2008 and 2025.
4. Conducting a detailed analysis of Knee Replacement wait times, including provincial differences and procedure volumes.
5. Comparing wait-time performance across the pre-COVID (2008–2019), pandemic (2020–2022), and recovery (2023–2025) periods.
6. Using simple linear regression to evaluate long-term trends in P50 and P90 wait times.

Provincial averages are descriptive averages across available provincial observations and should not be interpreted as official CIHI national estimates.
