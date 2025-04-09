---
name: Building Inventory Analysis
tools: [Python, Altair, Vega-Lite]
image: assets/pngs/buildings_per_decade.png
description: A data visualization project using building inventory data from the University of Illinois system.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# Building Inventory Visualization

This project uses building inventory data from Illinois state facilities to explore patterns in construction over time and building usage by agency.

## Visualization 1: Number of Buildings Constructed Per Decade

This bar chart shows the number of buildings constructed per decade, based on the “Year Constructed” column. I grouped the data by decade and visualized total building counts per decade using a clean, vertical bar chart. The chart helps show when periods of growth occurred. I used decade bins to reduce clutter and keep the axis readable.

## Visualization 2: Interactive – Average Square Footage by Usage Type

This interactive chart displays the average square footage for each usage category (e.g., “Office,” “Storage,” etc.), filtered by agency. Users can select an agency from a dropdown to see how space is allocated by use type. I used a bar chart to make size comparisons clear, and interactivity makes the visualization more personal and relevant for specific units.

## Explore the Data & Notebook

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/rrmack2/rrmack2.github.io/blob/main/building_inventory_analysis.ipynb" text="The Analysis" %}
</div>
