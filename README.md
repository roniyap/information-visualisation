# Global CO₂ Emissions Dashboard (1860–2020)

An interactive data visualisation dashboard exploring how global CO₂ emissions have evolved over time, which countries contribute the most, and how emissions relate to population and landmass.

## Overview

This project presents a multi-view dashboard combining four complementary visualisations to give users a comprehensive picture of CO₂ emissions across 160 years. It is designed to be accessible to general audiences while still offering depth for researchers, educators, and policymakers.

The dashboard uses a consistent colour scheme (continents colour-coded across views), a minimalist layout, tooltips for precise values, and shared interactive controls so the four views update together.

## Visualisations

### 1. Global CO₂ Emissions Trend (Line Chart)
Shows total global CO₂ emissions in billion tons from 1860 to 2020, with the line emphasising the steep upward trend. The x-axis uses 20-year intervals to keep the chart readable, and the y-axis is scaled in billion tons to avoid overwhelming numbers. Filterable by continent for regional comparisons.

### 2. Top 5 CO₂ Emitting Countries (Bar Chart)
A vertical bar chart of the five largest emitters at a given year, with bars colour-coded by continent. The year slider lets users watch countries overtake one another over time, and the continent filter narrows focus to a region. Limited to five bars to avoid clutter.

### 3. CO₂ Emissions per km² (Choropleth Map)
A world map encoding emission intensity per square kilometre using a red gradient to convey severity. Countries without data appear in grey. Tooltips display country name, land area, and exact emissions per km². The continent filter greys out other regions for focused analysis.

### 4. Per Capita Emissions vs. Population (Scatter Plot)
Plots CO₂ emissions per capita (tons per person) against population size (millions). Each country is a coloured circle, with circle size encoding total emissions. This view highlights small nations with disproportionately high per-capita emissions and aligns visually with the bar chart through shared continent colours.

## Interactive Controls

- **Year slider** — covers 1860 to 2020, updating the bar chart, map, and scatter plot in sync
- **Continent dropdown** — filters all four views to a single continent or shows all
- **Tooltips** — hover over any data point, bar, country, or circle to see exact values

## Data

The dashboard uses the [CO₂ Emission by Countries Year-Wise (1750–2022)](https://www.kaggle.com/datasets/moazzimalibhatti/co2-emission-by-countries-year-wise-17502022) dataset from Kaggle.

Although the original dataset starts in 1750, coverage before 1860 is sparse for most countries, so the analysis focuses on 1860 onward for clearer and more reliable insights.

## Audience

The dashboard is intended for:

- General audiences exploring how global emissions have changed
- Students and educators using it as a teaching aid
- Researchers comparing regional and per-capita emission patterns
- Policymakers looking at long-term trends and country-level contributions
