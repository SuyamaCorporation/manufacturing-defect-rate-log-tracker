# Manufacturing Defect Rate & Root-Cause Tracker

Production quality log that tracks batch defects, computes PPM, and visualises root-cause distribution with a Pareto chart and 7-entry trend.

## Key Features

- Log batches with ID, production count, defect count, 5M root-cause category (Machine/Material/Method/Manpower/Environment), and date
- Automatic PPM calculation (defects / production * 1,000,000) with colour-coded thresholds (green < 1 000, yellow < 5 000, red >= 5 000)
- Pareto bar chart showing defect count and cumulative percentage per root-cause category
- 7-entry PPM trend chart for quick visual inspection
- Sortable log table with per-row deletion; localStorage persistence of all entries
