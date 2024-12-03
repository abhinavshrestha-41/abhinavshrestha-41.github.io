---
layout: archive
permalink: /m_s_thesis/
title: "M.S. Thesis"
author_profile: true
redirect_from:
  - /resume
---
# Combining Multispectral and Three-Dimensional Data From Drone Imagery to Detect Forest Insect Damage: An Evaluation of a Novel Approach to Identify the Vertical Structure of Damage in Trees in the Northern Rocky Mountains, USA

Project description: My M.S. research project focused on evaluating methods of detecting forest insect damage and mortality using Unmanned Aerial Systems (UAS)-derived data products in conifer forests of the western United States. The project explored the utlity of point cloud data derived from Structure for Motion (SfM) for the classification and characterization of vertical tree damage of a UAS mission area. I used tools such as ArcGIS Pro, Agisoft Metashape, CloudCompare, and R and Python programming to create new algorithms and establish a novel methodology.   

Journal article: [![Static Badge](https://img.shields.io/badge/%20DOI%3A-10.3390%2Frs160813650-blue?style=plastic
    )](https://doi.org/10.3390/rs16081365)

Drone data used for this MS thesis was collected for a broader project assessing tree damage funded by the NASA Commercial SmallSat Data Acquisition Program (NASA CSDA, award #80NSSC21K115) (*see ['Collaborative Research'](#collaborative-research) section below*).  

> **The research for this project was conducted in the ancestral homelands of the Ksanka (Kootenai), Ql̓ispé (Pend d’Oreille), and Sélish (Salish) tribes of western Montana.**

A DJI Matrice 210 drone equipped with a <a href="https://support.micasense.com/hc/en-us/articles/360011389334-RedEdge-MX-Integration-Guide" target="_blank">MicaSense RedEdge-MX sensor</a> (5-band calibrated sensor) from Washington State University's <a href = "https://labs.wsu.edu/meddenslab/" target="_blank">Forest Ecosystem Dynamics Lab</a> (*research partners*) was used for imagery acquisition. UAS image acquisition mission was planned and operated by <a href="https://atstahl.github.io/">Dr. Amanda Stahl</a>. Here preview of the UAS-photogrammetry derived point cloud data I am working with (*data is displayed on CloudCompare*):

<img src="/files/MSProject_PC_data_demo.png" alt="Image showing point cloud data used in MS project displayed in CloudCompare" style="max-width: 100%; height: auto;">  

### Graphical abstract
<img src="/files/GraphicalAbstract.jpg" alt="Graphical abstract for journal article" style="max-width: 100%; height: auto;">  

### Interactive preview of methodology applied on the point cloud of a single tree

> *Use the left mouse button to tilt the 3D model and the mouse scroll wheel to zoom in and out.* 

True-color render and random forest classification of point cloud
<div style="display: flex;">
  <iframe src="/files/widgetRGB.html" width="50%" height="600" style="flex: 1;"></iframe>
  <iframe src="/files/widgetRFClass.html" width="50%" height="600" style="flex: 1;"></iframe>
</div>

> **Left panel:** True color representation of the point cloud. **Right panel:** RF classification; green is healthy, red is red, gray is gray, and black is shadow. 

Random forest classification probability and top-kill algorithm  
<div style="display: flex;">
  <iframe src="/files/widgetRFProb.html" width="50%" height="600" style="flex: 1;"></iframe>
  <iframe src="/files/widgetRFClass_TK.html" width="50%" height="600" style="flex: 1;"></iframe>
</div>


> **Left panel:** The probabilities of classes shown in left panel on the above interactive layout; darker colors represent higher probabilities of classification. **Right panel:** Top-kill algorithm applied to point cloud, 3D plane represents the height of top-kill detected by the algorithm.

*I presented a condensed version of my MS research for University of Idaho's [GIS day 2023](https://www.lib.uidaho.edu/gisday/) as a contributed talk.* 
> To view the recording of the presentation, please follow this link: 
<iframe width="560" height="315" src="https://www.youtube.com/embed/71AH3u_J9tQ?si=jxqHy1cbKtSn7eFY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


> To view the pdf of the presentation file, please follow this link: <a href="https://objects.lib.uidaho.edu/gisday/shrestha_gisday2023.pdf" target = "_blank">https://objects.lib.uidaho.edu/gisday/shrestha_gisday2023.pdf</a>

<hr>
