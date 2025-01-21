# PROJECT OVERVIEW: Philippines-Poverty-Choropleth-Map
  <ul>
    <li>Used ArcGIS Pro to map the sub-national spatial relationships of poverty in the Philippines.</li>
    <li>Scraped socioeconomic data from the Philippine Statistics Authority and the IBON Foundation.</li>
    <li>Feature classes digitized: Polygon (choropleth map of wage gap Philippine regions), Line(island grouping boundaries), Point (5 most impoverished cities).</li>
    <li>Monetary conversion: $1 CAD = 40.70 PHP.</li>
  </ul>
  
## Web Scraping
<ul>
<li><b>Wage Gap Data and Calculation:</b> https://www.ibon.org/flw-regl-2412/ </li>
<li><b>2023 Full Year Official Poverty Statistics of the Philippines:</b> https://psa.gov.ph/sites/default/files/phdsd/2023%20FY%20Official%20Poverty%20Statistics%20Publication_15August2024.pdf </li>
<li><b>Most Impoverished Highly Urbanized Cities (Poverty Incidence Among Famillies, %):</b></li>
  <ul>
    <li><b>Butuan:</b>12.2</li>
    <li><b>Iligan:</b>11.8</li>
    <li><b>Tacloban:</b>10.6</li>
    <li><b>Davao:</b>8.8</li>
    <li><b>Olongapo:</b>7.5</li>
  </ul>
</ul>

## Results and Discussion

![image](https://github.com/user-attachments/assets/d7f38abc-8433-42bd-af2b-775ff2176aef)

<i> <b>IMAGE DESCRIPTION:</b> Choropleth map of the Philippines covering poverty-related data, showing wage gap by regions, red points that represent the most impoverished cities, and dashed lines demarcating the three main island groups. With regards to the map design, even though the compass symbol and scale were not important in the context of this analysis, they were nevertheless resized and repositioned in a way that reduced whitespace as much as possible. Despite not being of the same administrative levels as provinces, regions, countries, etc., their font sizes were nevertheless resized as such to make their geographic location on the map more prominent (as they are important to the analysis). The choropleth colour scheme involved different tones of just one colour, as the region-by-region analysis only focused on one factor (wage gap).</i>

Based on the choropleth map, it appears that poverty is highly concentrated in the southern region of Mindanao, especially in the Bangsamoro Autonomous Region in Muslim Mindanao (very dark shade of blue). It is also interesting to note that 3 of the top 5 most impoverished cities are based in Mindanao. Of course, they are a multitude of ways to measure poverty, and this map is an oversimplification that does not account for differences within each regions, provinces, and island groups. Rigorous socioeconomic-based analysis such as exploring how poverty disproportionately impacts people from the peasant and urban poor classes, LGBTQ+ communities, Indigenous ethnic groups such as the Moro and Igorot peoples, and so forth, will have to compliment spatial analysis work like this one. Nevertheless, this is a good start, as the data is relatively recent and came from reliable and authoritative sources.
