---
layout: default
title: Coordinate Reference Systems
parent: Lecture Content
has_children: true
nav_order: 2
---


# Defining a Coordinate Reference Systems

A Coordinate Reference System (CRS) is *a coordinate-based system used to locate geographical entities*.  A CRS can be applied locally, regionally, or globally.  A Cartesian grid (think graph paper) is a simple 2D coordinate reference system for referencing locations on the surface of a flat plane.  A spherical coordinate system (think latitude/longitude) is a more complex 2D coordinate system for referencing locations on the surface of a sphere.  

<figure>
  <img src="content/images/cartSpherical.jpg"
  alt="cartesianSpherical">
  <figcaption><a href="https://postgis.net/workshops/postgis-intro/geography.html">Cartesian versus spherical, or geographic, coordinates.</a> <a href="https://postgis.net/">PostGIS.</a> </figcaption>
</figure>

---

# Why all world maps are wrong

This video gives a quick overview of some of the issues associated with making two dimensional maps of our three dimensional world.

<iframe width="560" height="315" src="https://www.youtube.com/embed/kIID5FDi2JQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<!-- 
# What **do** you need to know about projections?

**1)** Which types of projections are better sutied for certain circumastances.

**2)** The choice of projecton can have a significant impact on your analysis.

**3)** The choice of projecton can have a significant impact on how your maps are percieved.

**4)** What map scale means and how it relates to prjection choice.

# What **don't** you need to know about projections?

* Map projections are complex mathematical transformations.  You don't need to understand the intricacies of how they work.

* You also don't need to know what specific projection is the correct on for every situation.  You can ask someone or google it.  
 -->

