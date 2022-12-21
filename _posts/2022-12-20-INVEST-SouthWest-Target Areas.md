---
title: "INVEST South/West (ISW) Target Areas"
date: 2022-12-20
published: true
tags: [dataviz, matplotlib]
excerpt: "A Visual Overview of the INVEST South/West Initiative's Target Areas implicated by Tax-Increment Financing."
altair-loader:
  altair-chart-1: "charts/bigpic_1_chart.json"
  altair-chart-2: "charts/bigpic_2_chart.json"
  altair-chart-3: "charts/chi_alt_isw_map.json"
  altair-chart-4: "charts/chi_alt_isw_projcount.json"
toc: true
toc_sticky: true
read_time: false
---

# Brief Overview

In Fall 2019, Mayor Lori Lightfoot proposed the INVEST South/West Initiative (ISW). The plan targets approximately $2.2 Billion investment from a combination of public and private sources in 10 Chicago community areas/neighborhoods. By focusing on the revitalization of 12 commercial corridors, the INVEST South/West Initiative hopes to improve the local economies, state of housing, and quality of public realm in each of these areas. Approximately $220MM of funding for the ISW is projected to be generated via Tax-Increment Financing (TIF) Districts. The charts below simplifies all TIF funded projects in the city of Chicago nased on their location in priority community areas, as defined by the ISW. 

The data in this blog post was sourced entirely from the City of Chicago's open data portal via API.

<div id="altair-chart-1"></div>

The first chart shows that, on average, the approved amount of TIF funding per project is higher historically in non-priority community areas.

<div id="altair-chart-2"></div>

The second bar chart shows that projects in the priority community areas have historically recieved less TIF funding per project than projects outside of these areas.

## Target Areas

The map below is color scaled by ISW Priority Community Area. There are 15 primary community areas, 3 of which are formed by 2 or more Chicago neighborhoods. The Englewood primary community area is made up of the Englewood and West Englwood neighborhoods. The Bronze primary community area is made up for the Grand Boulevard, Oakland, and Kenwood neighborhoods. And, the Greater Roseland primary community area is made up the far south-side neighborhoods of Roseland, Pullman, and West Pullman.

<div id="altair-chart-3"></div>

The map below shows how TIF funded projects emanate from the Chicago Loop outward, with a considerable number of projects being located in the Loop and Near West Side.

<div id="altair-chart-4"></div>


