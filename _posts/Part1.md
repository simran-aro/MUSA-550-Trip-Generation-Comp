---
title: "Introduction, Inspiration and Background"
date: 2022-12-17
categories:
  - blog
tags:
  - Introduction
  - Indego
  - Blue Bikes
---
Philadelphia and Boston are often ranked in the top 20 bike-friendly cities in the US. Both have bikeshare systems, called Indego and BlueBikes respectively. This project looks at bike share data from both these cities, to explore trip data, demographic data, and which factors affect trip generation in both cities. These are then compared between Philadelphia and Boston to see the similarities and differences. The factors that are of importance in both the cities can be studied further— and used in strategies for bike planning in other places.

The inspiration behind this project was this article: ['The Most Bike-Friendly Cities in the U.S. (2022 Data)'](https://anytimeestimate.com/research/most-bike-friendly-cities-us-2022/#:~:text=We%20found%20the%20three%20most,%2C%20and%20San%20Jose%2C%20Calif.&text=Since%20the%20invention%20of%20the,of%20transportation%20across%20the%20globe.). I wanted to specifically see if the same factors affecting trips have similar importance in different cities. My hypothesis is that some factors are imperative to generating trips, but most are context specific. Additionally, the bike-share systems, Indego and Blue Bikes, might have different factors affecting ridership, as opposed to people riding their own bikes. Thus, I wanted to use some of the factors in this article to see if they apply to bike-share systems. 

This project is divided into three sections: 

The first explores demographic data in a map format. These maps are compared to bike trips marked spatially to see the correlation between the two.

The second explored weather data, and distances from various amenities. The articles mentions the importance of bike shops, thus, I wanted to specifically add this as a varible.

The third uses the random forest machine learning algorithm from Scikit-Learn to see which factors affect trip generation, and their importance. This is compared between the two cities.

![Blue-Bikes]({{ site.url }}{{ site.baseurl }}/assets/images/1200px-Bluebikes_Logo.png)
![Indego]({{ site.url }}{{ site.baseurl }}/assets/images/logo-1-300x119.png)
