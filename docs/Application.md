---
layout: default
title: Application
# parent: Module 1
has_children: True
nav_order: 3
---



1. TOC
{:toc}



# Getting Started with ArcGIS Pro:

## Revisiting the Foundations of Epidemiology

### Learning Objectives:

* Get your bearings with ArcGSI Pro
* Introduction to spatial analysis
* Brief overview of Digitizing and Georeferencing
* Create and share a map



## Accessing ArcGIS Pro

See the [Lab Access page](https://june-skeeter.github.io/GEOS270W1/docs/Labs.html)

## Saving Your Work
If you are using ArcPro installed on your own computer, you can manage your files however works best for you.  **However**, if you are working on a Geography lab computer, *follow the instructions on the lab details page closely.*

## Getting Started
The first step is opening ArcPro.  You can find it using the Windows start tab or search bar.  When ArcPro opens choose the Map under Blank Templates as shown below.  Then create your new project.  I've named mine Lab1_Project so I can easily identify it.  This will be the name of the folder your project resides in.  Set the location to an appropriate workspace.  I am working on my own computer, and my workspace workspace is "C:\GEOG270\2021_S1\Labs".  This is the location where the project folder will be reside.  If you are unfamiliar with the Windows operating system (OS), it might be helpful to take a few moments to learn about the differences between Windows and the OS (Mac, Linux) you are used to working with.  Once you set up a new project, close ArcGIS Pro for now.  

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="content/images/New_Project.png" title="Processes" scrolling="no" frameborder="0"

    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="content/images/New_Project.png" target="_blank">View Image in New Tab</a>



## Download Data.
Lets download the data we need and put it in our newly created project folder.  Follow [this link](https://github.com/June-Skeeter/Module1_GEOS270/blob/main/data/CholeraOutbreak_1854.gdb.zip).  Click the download button.  If a pop up appears, choose save, the file will be saved in the downloads folder.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="content/images/Download.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="content/images/Download.png" target="_blank">View Image in New Tab</a>

Open the windows file explorer (folder on bottom ribbon or search the start menu).  Navigate to the downloads folder.  You will see a folder called "CholeraOutbreak_1854.gdb", note the type "Compressed (zipped) Folder" and size 11709 KB.  Right click on the CholeraOutbreak_1854.gdb, choose a zip file manager, and select "Extract files".
* Zip files (.zip) are a method for compressing data so it can be stored and transfered more efficiently.  However, to work with the data, we have to extract it.
* On my computer, the 7-Zip is the .zip file manager.  If you are working on the geography department computers, you can uses PeaZip instead.  The specific options might differ, but the general principal is the same.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="content/images/Extract.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="content/images/Extract.png" target="_blank">View Image in New Tab</a>

In the pop up window, set your Lab1_Project folder as the Extract to location.
* The lab data is now downloaded and stored in your project folder.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="content/images/Unzip.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="content/images/Unzip.png" target="_blank">View Image in New Tab</a>