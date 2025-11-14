# Minnesota Traffic Monitoring Dashboard

Author: Emily Oor  
Dashboard: View the dashboard on [Tableau Public](https://public.tableau.com/views/TrafficPatterns_17619307813410/Dashboard12?:language=en-US&publish=yes).

Full Report: MinnesotaDOTproject.pdf

## Overview

An interactive Tableau dashboard developed for the Minnesota Department of Transportation (MnDOT) to analyze traffic volume across time, weather, and holidays.
The project aimed to make statewide traffic data accessible for planning, maintenance, and event management decisions.

## Methods

Traffic data (2012–2018) was cleaned and validated using Excel and Python, then visualized in Tableau Public.
Key steps included duplicate removal, standardizing weather categories, extending holiday labels, flagging unique hourly records, and documenting missing or incomplete days.

## Dashboard Features

- Year, month, and holiday filters
- Line, heatmap, bar, and treemap visualizations
- PDF export for easy sharing

## Key Insights

- Sharp winter traffic decline (Dec–Feb)
- Rain reduces traffic by ~70% vs. cloudy conditions
- Halloween shows the highest average traffic
- Holidays like Christmas and New Year’s Day show lowest volumes

## Impact

The dashboard supports data-informed scheduling, infrastructure planning, and event preparation, helping MnDOT allocate resources more efficiently and improve road safety.

## Repository Structure
```
.
├── data/                     # Raw and cleaned traffic data
├── notebooks/                # Python script for datetime validation
├── reports/                  # Final project report (PDF)
└── README.md                 # Project summary and links
```
