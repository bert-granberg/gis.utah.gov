---
status: publish
layout: page
tags:
  - dem
  - lidar
  - elevation
author:
  display_name: Rick Kelson
  email: rkelson@utah.gov
published: true
date: 2023-10-17 11:00:00
title: 2020 FEMA HQ Lidar Elevation Data
categories: []
---

![Sample]({% link images/lidar_femahq_2020.png %}){: .flex .flex--center .outline }

[![Project area map]({% link images/lidar_femahq_2020_coverage_sm.png %} "click for map")]({% link images/lidar_femahq_2020_coverage.png %}){:.inline-text-right}

{%- capture contact -%}
{%- include contact.html subject=page.title contact=site.data.contacts.elevation text='or by request from' -%}
{%- endcapture -%}
During 2020 UGRC, the Utah Division of Emergency Management, the Natural Resource Conservation Service (NRCS), the U.S. Forest Service (USFS), and the Federal Emergency Management Agency (FEMA) acquired [~13,686 square miles]({% link images/lidar_femahq_2020_coverage.png %}) of 2 and 8 points per meter Quality Level 1 & 2 LiDAR of portions Utah. The .5 and 1 meter resolution bare earth DEMs in .tif format have a 10.0cm vertical RMSE accuracy and are available for download. The LAS point clouds are available from [The National Map](https://apps.nationalmap.gov/downloader). This elevation data was collected between August and November, 2020.

<ul class="dotless">
  <li>
    <strong>
      {% include fa_icon.html download=true class="svg-inline--fa fa-w-16" %} <a href="https://raster.utah.gov/?catGroup=.5%20Meter%20%7B2020%20FEMA%20HQ%20LiDAR%7D,1%20Meter%20%7B2020%20FEMA%20HQ%20LiDAR%7D&title=FEMA%20HQ%202020%20LiDAR" target="_blank">Retrieve 2020 Bare Earth DTMs via Interactive Map</a>
    </strong>
  </li>
  <li>
    {% include fa_icon.html download=true class="svg-inline--fa fa-w-16" %} Download project <a href="https://storage.googleapis.com/state-of-utah-sgid-downloads/lidar/femahq-2020/FEMAHQ_2020_Reports.zip" target="_blank">Reports</a> and <a href="https://storage.googleapis.com/state-of-utah-sgid-downloads/lidar/femahq-2020/FEMAHQ_2020_Metadata.zip" target="_blank">Metadata</a>
  </li>
  <li>
    {% include fa_icon.html download=true class="svg-inline--fa fa-w-16" %} Download <a href="https://storage.googleapis.com/state-of-utah-sgid-downloads/lidar/femahq-2020/FEMAHQ_2020_shps.zip" target="_blank">shapefiles</a> of project area, tile indices, and breaklines
  </li>
</ul>

The naming convention for the tiles are based off the [U.S. National Grid (USNG)](https://www.fgdc.gov/usng/how-to-read-usng/index_html).

This elevation data has a UTM NAD83 (2011) zone 12 north meters NAVD88(GEOID12) projection.

{% include contact.html subject=page.title contact=site.data.contacts.elevation %}
