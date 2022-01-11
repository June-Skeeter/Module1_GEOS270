---
layout: default
title: Spatial Analysis
parent: Foundations of Epidemiology
grand_parent: Lab Application
nav_order: 3
---

# Spatial Analysis
{: .no_toc }

We already know the Broad St. pump was the source of the outbreak, but lets explore a couple analysis techniques we could use to identify the source of an outbreak.

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

# Central Tendency

There are numerous ways to analyze the spatial distribution of a dataset.  The [Mean Center](https://pro.arcgis.com/en/pro-app/latest/tool-reference/spatial-statistics/mean-center.htm) and [Directional Distribution](https://pro.arcgis.com/en/pro-app/latest/tool-reference/spatial-statistics/directional-distribution.htm) are two of the simplest measures.  Mean center gives you a single point around which the directional distribution creates an ellipse to show directional trends in the data.  You don't have to calculate these statistics, but skim the linked pages and look at the example below to understand what these methods do.
* They can be weighted (eg. by the number of deaths per address).
* These measures roughly identify the Broad St. Pump as the source of the outbreak, as shown in the figure below.
  * However, they are rudimentary metrics at best.  They could be used to identify multiple point sources for example.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="content/images/Distribution.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="content/images/Distribution.png" target="_blank">View Image in New Tab</a>

---

# Kernel Density

A more advanced method is [Kernel Density](https://pro.arcgis.com/en/pro-app/latest/tool-reference/spatial-analyst/kernel-density.htm), which gives you a magnitude (eg. number of deaths) per unit area (eg. hectare).  Follow the steps as outlined and refer to the video below to calculate the Kernel Density of cholera deaths in Soho.

**1)** Click the Analysis tab and select Tools.  In the Geoprocessing pane, search for and open the Kernel Density tool.
* The Geoprocessing pane is where you can find all the different spatial analysis tools in ArcGIS Pro.

**2)** Set Deaths as the input and COUNT as the Population Field.
* The population field weights the calculations by the number of deaths at each address.

**3)** Rerun the analysis multiple times, playing around with different Output cell sizes and Area units.  When you are done exploring the effects of cell size and units, calculate the Kernel Density with a cell size of 5 and unit of Hectares.
* A Hectare is 10,000 m<sup>2</sup>, or about the area a small city block.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="content/videos/KD.mp4" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="content/videos/KD.mp4" target="_blank">View Image in New Tab</a>

---

# Save your project.

Click Save in the top left of the Arc Pro window.
