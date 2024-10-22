# Global CO2 Emissions Dashboard (1750-2022)

## Overview

This project analyzes historical and modern CO2 emissions data (1750-2022) to help identify key trends, patterns, and drivers of global carbon emissions. The goal was to create an interactive Tableau dashboard that visualizes global CO2 data and enables users to explore emission patterns and their relationship with population and climate.

The dashboard provides the following insights:
- Percentage share of CO2 emissions by year for the top contributing countries.
- CO2 per capita at the country level for the year 2021.
- Comparison of CO2 emissions with population, sized by the temperature change from CO2.

## Objectives
1. **Data Profiling and Quality Assurance**: Reviewed and cleaned the dataset, excluding null ISO code values and ensuring all CO2-related fields were numeric.
2. **Data Preparation**: Converted CO2-related fields into continuous numeric types and created a parameter for filtering the top countries by CO2 emissions.
3. **Data Visualization**: Built visualizations to highlight key insights:
   - A line chart displaying the % share of CO2 emissions by year for the top 10 countries.
   - A world map showing CO2 emissions per capita for the year 2021.
   - A scatter plot comparing CO2 emissions and population, sized by temperature change.
4. **Dashboard Development**: Combined all visualizations into a cohesive dashboard, including dynamic filtering by country and an adjustable "Top N" parameter.

## Features
- **Interactive Line Chart**: Displays the share of global CO2 emissions over time for the top countries, filtered dynamically using the Top N parameter.
- **CO2 Per Capita Map**: Shows CO2 per capita for each country in 2021 with a divergent color scale.
- **CO2 and Population Scatter Plot**: Compares CO2 emissions with population, with bubbles sized based on temperature change.
- **Filters**: Country-level filter applied to all sheets to allow interactive exploration of the data.
- **Fully Interactive Dashboard**: Users can explore data across multiple dimensions, with custom parameters and filters.

## Tools and Technologies
- **Data Source**: CO2 emission data (1750-2022) CSV file.
- **Visualization**: Tableau (including line charts, maps, and scatter plots).
- **Languages**: Tableau dashboard development, data visualization.

## Insights
- The dashboard reveals key contributors to global CO2 emissions, with historical patterns showing an increasing concentration in certain regions over time.
- CO2 per capita trends vary significantly between countries, with certain regions showing disproportionately high emissions relative to their population.
- The relationship between CO2 emissions and population is complex, with larger populations not always correlating to higher emissions.

## Live Dashboard
Explore the live dashboard [here](https://public.tableau.com/shared/D2XT55BPD?:display_count=n&:origin=viz_share_link).
