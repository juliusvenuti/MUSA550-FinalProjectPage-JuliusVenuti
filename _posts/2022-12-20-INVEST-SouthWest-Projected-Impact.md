---
title: "Projecting the Performance of TIF under INVEST South/West (ISW)"
date: 2022-12-20
published: true
tags: [dataviz, matplotlib]
excerpt: "Tax-Increment Financing's potential performance based on prior TIF funded projects in the INVEST South/West Initiative's Primary Community Areas."
altair-loader:
  altair-chart-1: "charts/bigpic_3_chart.json"
  altair-chart-2: "charts/bigpic_4_chart.json"
  altair-chart-3: "charts/Bars.json"
  altair-chart-4: "charts/bigpic_3_5_chart.json"
  altair-chart-5: "charts/bigpic_4_5_chart.json"
toc: true
toc_sticky: true
read_time: false
---

## TIFs in the Primary Community Areas

There have been 146 projects completed with the assistance of TIF funding in the primary community areas targeted by the ISW Initiative. With approximately $220MM of TIF funding currently slotted to contribute towards the creation of development projects in these primary community areas, an additional 86 projects have the potential to be created based on TIF Funding Ratios, Aggregate Development Costs for TIF projects, and the number of TIF projects developed in the past. See the charts below for how the past and potential of TIF financing of projects in these community areas breaksdown. 

<div id="altair-chart-3"></div>

The following bar charts breakdown, by priority community area, the projected and historical projects created and aggregate total development costs associated with all TIF projects in each respective area. Based on a combination of historical development cost by area and the significantly less approved TIF amounts for projects under the ISW Initiative, this analysis identifies that investment trends across the community areas could prioritize TIF projects that in community areas that recieved less funding in the past. For example, South Chicago ranked 2nd across the priority community areas in aggregate project costs, but is projected to create 0 projects if the $220MM in approval TIF funding is spread equally across each of the priortiy commmunity areas.

<div id="altair-chart-1"></div>
<div id="altair-chart-4"></div>


<div id="altair-chart-2"></div>
<div id="altair-chart-5"></div>

The second bar chart shows that projects in the priority community areas have historically recieved less TIF funding per project than projects outside of these areas.

## A Note on the Predictive Model

Initially, this analysis was to include a predictive model that uses the scikit-learn package to determine the variables that influence the approved amount of TIF projects throughout the City of Chicago. That said, through several stages of trial and error this component of the project proved itself to be irrelevant and thus overall inconclusive. This is likely due to the historically political nature of TIF funding allocations and the program's use as a gap-financing source that is dependent largely on potential financing needs of prospective developments, rather than market, demographic, and environemntal factors. While the log distance charts created through this attempt and learning process are interesting, the importance of each of these varuiables as well as the deomgraphic and economic ones provided by the Census Bureau were difficult to discern. The charts can be viewed below.

![distance-chicago-loop]({{ site.url }}{{ site.baseurl }}/assets/images/logDistLoopMap.png)
![distance-cta]({{ site.url }}{{ site.baseurl }}/assets/images/logDistCTAMap.png)
![distance-city-land]({{ site.url }}{{ site.baseurl }}/assets/images/logDistCityLandMap.png)



