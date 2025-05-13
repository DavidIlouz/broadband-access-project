# Broadband Access and Wealth in U.S. Counties

This is my final project for Johns Hopkins University's *Intro to Programming and Data Management* course.

## Overview

This project investigates whether wealth is a reliable predictor of broadband access across U.S. counties. It uses public data from the FCC and U.S. Census Bureau and was completed in R using Quarto.

## Files Included

- `david_ilouz_final.qmd` – the Quarto source file (run this to generate the report)
- `david_ilouz_final.pdf` – rendered PDF output
- `bdc_us_fixed_broadband_summary_by_geography_J24_29apr2025.csv` – broadband data from the FCC (I have removed most of the rows included n the original data set to include only those that will be used in this project due to size limitations)
- `README.md` – this file

## Data Sources

- U.S. Census Bureau. 2025. “American Community Survey (ACS) 5-Year Data (2018–2022).” [Link](https://www.census.gov/data/developers/data-sets/acs-5year.html)
- Federal Communications Commission. 2024. “Fixed Broadband Summary by Geography Type.” [Link](https://broadbandmap.fcc.gov/data-download/nationwide-data)

## Reproducibility

This project is fully reproducible. To run it:
1. Clone the repo using GitHub Desktop or `git clone`
2. Open the `.qmd` file in RStudio
3. Run the Quarto file to regenerate all results

Note: You may need to load a Census API key using the `census_api_key()` function from the `tidycensus` package.
