
# Logistics Root-Cause Analysis

## Project Overview
A Python-based logistics analytics project investigating
a decline in On-Time Delivery (OTD) for a simulated
Kolkata freight company.

## Objectives
- Analyze delivery performance.
- Investigate warehouse, vehicle, route, hub and service factors.
- Perform statistical hypothesis testing.
- Build a regression model.
- Estimate driver contributions using a counterfactual.
- Prototype a weekly early-warning system.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Google Colab

## Key Finding
The simulated OTD declined from 55.33% to 41.36%.
The warehouse counterfactual estimated that the
warehouse processing increase explained 96.71%
of the simulated decline.

This is a designed simulation result, not verified
evidence about a real logistics company.

## Files
- Logistics_Root_Cause_Analysis.ipynb: analysis notebook
- cleaned_logistics_data.csv: integrated dataset
- weekly_early_warning.csv: weekly monitoring output
- hypothesis_log.csv: hypothesis testing log
- driver_tree.png: driver-tree visualization
- root_cause_management_report.md: management report

## Limitations
The dataset is simulated. The early-warning system
has not been validated for four-week advance detection.
Festive effects and real-world causality have not
been independently established.

## How to Run
Open the notebook in Google Colab and run the cells
from top to bottom.
