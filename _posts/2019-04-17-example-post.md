---
title: "Part 1: Exploring Demographic Data and Bike-Share Trips in Philadelphia and Boston"
date: 2022-12-18
published: true
tags: [Philadelphia, Boston, Demographics]
excerpt: 
hv-loader:
  hv-chart-1: ["assets/images/phl_bike_pct.html", "500"],
  hv-chart-2: ["assets/images/bst_bike_pct.html", "500"]
toc: true
toc_sticky: true
read_time: false
---

# Philadelphia

Philadelphia's bike-share system is called Indego. It currently has 140 stations across the city. It has started in 2015, and has added several stations and types of bikes since then. In this section, we will look at different demographic data of Philadelphia, and compare it with where most bike trips happen in the city.

## Methodology

Indego shares its trip data by quarter. The format is is .csv files, and had to be downloaded manually. Since I am only look at trips during the height of the pandemic, only 2020 and 2021 data is downloaded for this analysis. This data was spatially plotted within census tracts of Philadelphia, since I am using census tracts as my unit of analysis. Then, census data for age, income, total population was downloaded, in addition to average commute time to work, and percentage of workers above 16 who commute using bike. This data was spatially joined to trip data to create the following maps.

Similarly, for Boston, similar analysis was performed. Blue Bikes data comes monthly, and was downloaded manually. The additional work for Boston was to include census tracts of Cambridge as well, since half the trips and stations occur in Cambridge. For this, all census tracts in Suffolk County (Boston's County) and Middlesex County (Cambridge's County) were downloaded and plotted.

## Percentage of Commuters Using a Bike

<div id="hv-chart-1"></div>
<div id="hv-chart-2"></div>


