# PROJECT OVERVIEW: Philippines Poverty Choropleth Map


## Table of Contents
* [Overview](#overview)
* [Code and Setup](#code-and-setup)
* [Web Scraping](#web-scraping)
* [Map Development](#map-development)
* [Results](#results)
* [Discussion](#discussion)
* [Assumptions and Caveats](#assumptions-and-caveats)
* [Credits and Acknowledgements](#credits-and-acknowledgements)

---

## Overview

  <ul>
    <li>Used ArcGIS Pro to map the sub-national spatial relationships of poverty in the Philippines.</li>
    <li>Scraped socioeconomic data from the Philippine Statistics Authority and the IBON Foundation.</li>
    <li>Feature classes digitized: Polygon (choropleth map of wage gap Philippine regions), Line(island grouping boundaries), Point (5 most impoverished cities).</li>
    <li>Monetary conversion: $1 CAD = 40.70 PHP.</li>
  </ul>

---

## Code and Setup

[Download ArcGIS Pro (version 3.4), must be signed in.](https://pro.arcgis.com/en/pro-app/latest/get-started/install-and-sign-in-to-arcgis-pro.htm)

If you'd like to fork or run this locally:

```bash
git clone https://github.com/Francis-Calingo/Philippines-Poverty-Choropleth-Map.git
cd Philippines-Poverty-Choropleth-Map
```


[<b>Back to Table of Contents</b>](#table-of-contents)

---

## Web Scraping
<ul>
<li><b>Wage Gap Data and Calculation:</b> https://www.ibon.org/flw-regl-2412/ </li>
<li><b>2023 Full Year Official Poverty Statistics of the Philippines:</b> https://psa.gov.ph/sites/default/files/phdsd/2023%20FY%20Official%20Poverty%20Statistics%20Publication_15August2024.pdf </li>
<li><b>Most Impoverished Highly Urbanized Cities (Poverty Incidence Among Families, %):</b></li>
  <ul>
    <li><b>Butuan:</b>12.2</li>
    <li><b>Iligan:</b>11.8</li>
    <li><b>Tacloban:</b>10.6</li>
    <li><b>Davao:</b>8.8</li>
    <li><b>Olongapo:</b>7.5</li>
  </ul>
</ul>

[<b>Back to Table of Contents</b>](#table-of-contents)

---

## Map Development

| Layer Type  | Layer Description | Layer Symbology | Number of Elements | 
| ------------- | ------------- | ------------- | ------------- |
| Polygon | Regions of the Philippines | Blue gradient colour based on wage gap data, shapes based on shapefile data | 17 |
| Line | Boundaries demarcating the Philippines' 3 major island groups | Dashed blue lines with labels | 2 |
| Point | 5 most impoverished cities in the Philippines | Red dots with black outline, and labels | 5 |

Other elements:
* North compass
* Map legend
* Scale (in kilometres)

[<b>Back to Table of Contents</b>](#table-of-contents)

---

## Results

![image](https://github.com/user-attachments/assets/d7f38abc-8433-42bd-af2b-775ff2176aef)

<i> <b>IMAGE DESCRIPTION:</b> Choropleth map of the Philippines covering poverty-related data, showing wage gap by regions, red points that represent the most impoverished cities, and dashed lines demarcating the three main island groups. With regards to the map design, even though the compass symbol and scale were not important in the context of this analysis, they were nevertheless resized and repositioned in a way that reduced whitespace as much as possible. Despite not being of the same administrative levels as provinces, regions, countries, etc., their font sizes were nevertheless resized as such to make their geographic location on the map more prominent (as they are important to the analysis). The choropleth colour scheme involved different tones of just one colour, as the region-by-region analysis only focused on one factor (wage gap).</i>

* Three of the 5 most impoverished cities in the Philippines were located in Mindanao.
  
* The most impoverished regions are also concentrated in Mindanao, with Bangsamoro (dark blue) being a significant outlier.
  
[<b>Back to Table of Contents</b>](#table-of-contents)

---

## Discussion

The concentration of poverty in Southern Philippines means that policymakers must examine the unique socioeconomic circumstances of that island group, determine their relationships with poverty, and why regions such as Bangsamoro have extremely high rates of poverty, especially in comparison to its northern counterparts. Some considerations for policymakers and NGOs:

* **Demographics**: The island group may have a high concentration of Indigenous people ("katutubo"), whose livelihoods continue to be threatened by issues such as land-grabbing and development projects that have an effect of displacing communities. All levels of government must engage in comprehensive and constructive conversations with Indigenous communities to ensure that they are doing socieconomically well.
  
* **Conflicts**: The island group has faced continuous instability, with continued fighting between government and rebel forces. The government must continue to negotiate long-lasting peace in Mindanao to spur economic growth that will improve the lives of its people.

* **Geographic Considerations**: The difficulty of traveling from Mindanao to the National Capital Region may be a factor to consider, especially if wealth, infrastructure development, and national attention continues to be concentrated in a few areas, including the National Capital Region in Luzon.

[<b>Back to Table of Contents</b>](#table-of-contents)

---

## Assumptions and Caveats

There are a multitude of ways to measure poverty, and this map is an oversimplification that does not account for differences within each region, province, and island group. Rigorous socioeconomic-based analysis such as exploring how poverty disproportionately impacts people from the peasant and urban poor classes, LGBTQ+ communities, Indigenous ethnic groups such as the Moro and Igorot peoples, and so forth, will have to complement spatial analysis work like this one. Nevertheless, this is a good start, as the data is relatively recent and came from reliable and authoritative sources.

[<b>Back to Table of Contents</b>](#table-of-contents)

---

## Credits and Acknowledgements

“GIS, Mapping, and Spatial Analysis.” University of Toronto. Coursera, https://www.coursera.org/specializations/gis-mapping-spatial-analysis

"Project 1 - Mapping Nigerian states by GDP". Uploaded by Umar Yusuf, 2022-02-08. YouTube, https://www.youtube.com/watch?v=X0b2DsV-6O4&list=PLeHfkOtgcB2vCWjcPRxbhF5e_exR_DMWa

[<b>Back to Table of Contents</b>](#table-of-contents)

