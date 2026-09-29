# Airtel Potential Inactive Cell Detection & Neighbor Traffic Impact Analysis

## Overview

This project focuses on identifying telecom cells showing potential signs
of inactivity or localized traffic degradation using data-driven analysis.

The analysis examines SIM traffic, session traffic, temporal variations,
cell-level performance and neighboring-cell behavior to distinguish
potential inactive cells from normal traffic fluctuations.

## Objectives

- Identify cells showing abnormal traffic decline
- Classify cell health conditions
- Analyze neighboring cell traffic impact
- Calculate recovery/traffic redistribution patterns
- Provide actionable insights through a dashboard

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Tableau
- Excel/CSV

## Methodology

1. Data Cleaning & Preprocessing
2. Cell-Level Traffic Analysis
3. Traffic Decline Detection
4. Cell Health Classification
5. Geographic Neighbor Identification
6. Neighbor Traffic Impact Analysis
7. Dashboard Development

## Key Analysis

The project analyzes SIM and session traffic across telecom cells
and compares traffic behavior across multiple time periods.

Potentially problematic cells are further evaluated using neighboring
cell behavior to understand whether traffic loss may have shifted to
nearby cells.

## Dashboard

The final dashboard provides filters and views for:

- Circle
- LAC
- Cell ID
- Cell Status
- Confidence
- Date/Period
- Neighbor Traffic Impact

## Disclaimer

This project is intended for analytical and educational purposes.
Potential inactive-cell identification represents an analytical
indication and should be validated against operational/network outage
logs before being treated as a confirmed outage.
