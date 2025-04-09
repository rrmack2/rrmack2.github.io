---
name: Facebook Ego Network Analysis
tools: [Python, Altair, Vega-Lite]
image: assets/pngs/facebook_network.png
description: An interactive data visualization project exploring Facebook friendships using Altair and Vega-Lite.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# Facebook Ego Network Analysis

This project visualizes the **ego-Facebook dataset**, which includes anonymized friendship connections. Using Python, NetworkX, Pandas, and Altair (with Vega-Lite), I created two visualizations to better understand the structure and reach of users within the network.

---

## Visualization 1: Facebook Ego Network Layout

This chart shows a force-directed layout of the Facebook ego network. Each node represents a user, and each edge is a friendship connection. The layout was created with NetworkX’s spring layout algorithm, and nodes are colored by their degree (number of friends), using the viridis color scale. This allows us to see which users are more central or well-connected in the network.

---

## Visualization 2: Interactive Degree Histogram

This interactive histogram visualizes how many friends each user has. Users can click and drag to select a range of degrees, which filters the bars in real time. This interactivity allows us to explore the distribution more clearly and discover outliers or highly connected individuals.

---

## Explore the Data & Code

Below are links to the dataset and the Python notebook used to generate these visualizations:

```
<div class="left">
{% include elements/button.html link="https://snap.stanford.edu/data/facebook_combined.txt" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/rrmack2/rrmack2.github.io/blob/main/facebook_analysis.ipynb" text="The Analysis" %}
</div>
```