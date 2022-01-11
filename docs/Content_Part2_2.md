---
layout: default
title: Projected Coordinate Systems
parent: Coordinate Reference Systems
# has_children: true
grand_parent: Lecture Content
nav_order: 2
---

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

# Projected Coordinate Systems

There are many differnt types of Map Projections.  They are classified by how the are projected onto a surface and what kind of deformatoins they impose.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="content/Projection.html" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="content/Projection.html" target="_blank">View slides in new tab</a>


## Choosing a Projection

| Projection Category | Properties | Common Uses |
| :------------- | :-------------: | -------------: |
| Conformal | Preserves local shapes and angles | Topographic maps, navigation charts, weather maps |
| Equal Area | Preserves areas | Dot density maps, thematic maps |
| Equidistant| Preserves distance from one or two specified points to all other points on the map | Maps of airline distances, seismic maps showing distances from an earthquake epicenter |
| Azimuthal | All directions are true from a single specified point (usually the center) to all other points on the map | Navigation and route planning maps |
| Compromise | No point is completely distortion free; distortion is minimized near the center and along the equator | World maps |

