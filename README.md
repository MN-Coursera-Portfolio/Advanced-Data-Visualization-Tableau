# Advanced Data Visualization with Tableau - New York Airbnb Analysis

## Project Overview
This project focuses on analyzing the New York City Airbnb dataset (2019) to extract business insights regarding pricing trends, room type distributions, and geographical performance. The analysis was conducted as the final requirement for the "Advanced Data Visualization with Tableau" course.

## Business Objectives
- Build interactive hierarchies for geographical and room-type analysis.
- Implement Level of Detail (LOD) expressions to compare listing prices against neighborhood averages.
- Develop a comprehensive dashboard for stakeholders to identify high-value investment corridors.

## Key Technical Implementations
- **Hierarchies**: Implemented structured drill-down capabilities for 'Neighborhood Group -> Neighborhood' and 'Room Category -> Room Type'.
- **Calculated Fields**: Created metrics for 'Average Price per Night', 'Total Revenue Estimate', and 'Occupancy Rate'.
- **LOD Calculations**: Used `{ FIXED [Neighborhood] : AVG([Price]) }` to identify pricing anomalies.
- **Interactivity**: Integrated map-based tooltips and dashboard actions for dynamic filtering.

## Visualization Highlights
- **Neighborhood Map**: Geographic pricing distribution across New York's boroughs.
- **Revenue Heatmap**: Identifying top-performing clusters in Manhattan and Brooklyn.
- **Trend Analysis**: Correlation between 'Reviews per Month' and 'Price Point'.

## Portfolio Link
The interactive dashboard is available on [Tableau Public](https://public.tableau.com/app/profile/coursera.learner/viz/NewYorkAirbnbPricingReport/Dashboard).

## Tools Used
- Tableau Desktop / Public
- NYC Airbnb Open Data (2019)
- Python (for logic verification)
