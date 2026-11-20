# python-data-cleaning-bookings
Data cleaning and exploratory analysis of a raw booking dataset using Python (pandas and matplotlib).

# Python Data Cleaning & Exploratory Analysis (Pandas)

## Overview
An end-to-end data cleaning, summary analysis, and month-wise visualization workflow built in Python (`pandas`, `numpy`, `matplotlib`, and `io`) on a 50-row, 5-column raw booking dataset.

## Data Quality Issues Handled
- **Missing Values:** Handled missing customer names and incomplete numeric entries.
- **Invalid & Text Values:** Converted word-based values and coerced non-numeric text into missing values for clean numeric processing.
- **Outliers & Invalid Ranges:** Filtered out unrealistic ages and invalid booking amounts.
- **Date Standardization:** Parsed date formats cleanly and handled invalid dates without breaking the pipeline.

## Files in This Repository
- `travel_booking_cleaning.ipynb` — Complete code, exploration outputs, monthly summary, and bar chart
- `raw_bookings_dirty.csv` — Original raw dataset before cleaning
- `clean_5cols_50rows.csv` — Final cleaned dataset ready for analysis

## What Was Done
- Inspected raw booking data (`raw_bookings_dirty.csv`) for missing values, mixed data types, invalid dates, and outliers.
- Cleaned the dataset in Python (`travel_booking_cleaning.ipynb`) and generated a month-wise summary and bar chart.
- Exported the cleaned dataset as `clean_5cols_50rows.csv`.


