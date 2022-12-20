---
title: "Chicago Community Areas"
date: 2022-12-20
published: true
tags: [dataviz, matplotlib]
excerpt: "This is an example blog post that embeds a matplotlib image."
altair-loader:
  altair-chart-1: "charts/chi_alt_map_pop.json"
  altair-chart-2: "charts/chi_alt_map_workage.json"
  altair-chart-3: "charts/chi_alt_map_unemployment.json"
  altair-chart-4: "charts/chi_alt_map_white.json"
  altair-chart-5: "charts/chi_alt_map_black.json"
  altair-chart-6: "charts/chi_alt_map_lathisp.json"
  altair-chart-7: "charts/chi_alt_map_asian.json"
toc: true
toc_sticky: true
read_time: false
---

# Demographic and Economic Data by Chicago Community Area

Below, we show core dempgraphic data for the City of Chicago by neighborhood using the Altair package. The map is color scaled by total population and indicates that the North- and West-sides of the city are the most populated areas.

The demographic data was sourced from the 2021 ACS 5-year estimate tables DP05 and DP03. The geometric data was sourced from the City of Chicago's open data portal.

<div id="altair-chart-1"></div>

## Working Age Population & Unemployment Rates

The maps below are color scaled by working age population (ages 20-44) and unemployment rates.

<div id="altair-chart-2"></div>
<div id="altair-chart-3"></div>

These maps indicate that the North-side of the city has the greatest perecentage of prime age workforce population, and that the South- and West-sides have the highest unemployment rates city-wide.

## Racial/Ethnic Distribution of Chicago's Total Population

The maps below are color scaled by the white, black, latino/a/x, and asian populations of Chicago. These maps distinctly represent the distribution of population by race in Chicago.

<div id="altair-chart-4"></div>
<div id="altair-chart-5"></div>
<div id="altair-chart-6"></div>
<div id="altair-chart-7"></div>

All of these maps in combination reflect the INVEST South/West Initiative's primary focus on racial and economic equity through targeted neighborhood investment.
