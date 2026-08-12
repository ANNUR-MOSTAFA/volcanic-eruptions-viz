# Volcanic Eruptions in the Holocene Period — Interactive Data Visualisation

A coded, interactive data visualisation exploring 1,500+ volcanic eruptions recorded over the last 10,000 years, built with Vega-Lite and hosted live on GitHub Pages.

**Live demo:** https://annurmostafa01.github.io/FIT3179-A2/

## Overview

The dataset (sourced from the Smithsonian Institution's Global Volcanism Program) records the location, type, elevation, and features of volcanoes that have erupted during the Holocene period. The goal was to design a set of coded, interactive visual idioms that let a reader explore geographic, categorical, and quantitative patterns in the data — not just present static charts.

## What I did

- **Interactive dot map:** plotted every recorded eruption on a world map using geographic coordinates, with hue encoding elevation and hover tooltips revealing detailed eruption info per point
- **Comparative bar chart:** highest/lowest elevation by geographic region, to surface regional patterns at a glance
- **Scatter plot:** elevation by volcano type, to compare eruption characteristics across eruption categories
- Justified each idiom choice explicitly — e.g. choosing a dot map over a choropleth or proportional symbol map because of how sparse the geographic distribution is and how difficult it would be to encode elevation accurately as symbol size
- Applied the **Five Design Sheet (FDS) methodology** to iterate through multiple layout concepts before settling on a final design
- Designed with deliberate attention to colour palette consistency, layout/whitespace, figure-ground clarity, and typography hierarchy

## Tech stack

`Vega-Lite` · `JavaScript` · `HTML/CSS` · GitHub Pages (hosting)

## Key takeaway

Choosing the right idiom is as much about ruling things out as picking a favourite — the dot map was chosen specifically *because* a proportional symbol map would have made elevation (a continuous variable) unreliable to compare visually across sparse, unevenly distributed points. Justifying design decisions this way, rather than just picking a "nice-looking" chart, was the main skill this project reinforced.

---
*Individual assignment, Monash University Malaysia — FIT3179 Data Visualisation*
