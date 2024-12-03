---
layout: archive
permalink: /research/
title: "Research"
author_profile: true
redirect_from:
  - /resume
---
# Graduate Research  

### M.S. Project @University of Idaho: 

> **Title**: [*Combining Multispectral and Three-Dimensional Data From Drone Imagery to Detect Forest Insect Damage: An Evaluation of a Novel Approach to Identify the Vertical Structure of Damage in Trees in the Northern Rocky Mountains, USA*](https://www.proquest.com/dissertations-theses/combining-multispectral-three-dimensional-data/docview/2903210004/se-2?accountid=9758)

Project description: My M.S. research project focused on evaluating methods of detecting forest insect damage and mortality using Unmanned Aerial Systems (UAS)-derived data products in conifer forests of the western United States. The project explored the utlity of point cloud data derived from Structure for Motion (SfM) for the classification and characterization of vertical tree damage of a UAS mission area. I used tools such as ArcGIS Pro, Agisoft Metashape, CloudCompare, and R and Python programming to create new algorithms and establish a novel methodology.   

Drone data used for this MS thesis was collected for a broader project assessing tree damage funded by the NASA Commercial SmallSat Data Acquisition Program (NASA CSDA, award #80NSSC21K115) (*see ['Collaborative Research'](#collaborative-research) section below*).  

> **The research for this project was conducted in the ancestral homelands of the Ksanka (Kootenai), Ql̓ispé (Pend d’Oreille), and Sélish (Salish) tribes of western Montana.**

A DJI Matrice 210 drone equipped with a <a href="https://support.micasense.com/hc/en-us/articles/360011389334-RedEdge-MX-Integration-Guide" target="_blank">MicaSense RedEdge-MX sensor</a> (5-band calibrated sensor) from Washington State University's <a href = "https://labs.wsu.edu/meddenslab/" target="_blank">Forest Ecosystem Dynamics Lab</a> (*research partners*) was used for imagery acquisition. UAS image acquisition mission was planned and operated by <a href="https://atstahl.github.io/">Dr. Amanda Stahl</a>. Here preview of the UAS-photogrammetry derived point cloud data I am working with (*data is displayed on CloudCompare*):

<img src="/files/MSProject_PC_data_demo.png" alt="Image showing point cloud data used in MS project displayed in CloudCompare" style="max-width: 100%; height: auto;">  

> *I am currently developing the journal article for my project. In the meantime, checkout the graphical abstract for the journal article in preparation for this project and example data product from the methodlogy applied on the point cloud of a single tree*

### Graphical abstract
<img src="/files/GraphicalAbstract.jpg" alt="Graphical abstract for journal article" style="max-width: 100%; height: auto;">  

Journal article: [![Static Badge](https://img.shields.io/badge/%20DOI%3A-10.3390%2Frs160813650-blue?style=plastic
    )](https://doi.org/10.3390/rs16081365)

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

## Collaborative research:  

**Graduate Research Assistant**, <a href = "https://www.earthdata.nasa.gov/esds/csda" target="_blank">NASA Commercial SmallSat Data Analysis (NASA CSDA) project</a> 
<br>
Project title: *Using commercial satellite imagery to study insect outbreaks in the US: Outbreak characteristics and evaluation of Landsat-based algorithms.*  
Project decription: This is a collaborative research project with researchers from the University of Idaho, Washington State University, and the US Forest Service Rocky Mountain Research Center.  
Principle Investigator: <a href = "https://environment.wsu.edu/arjan-meddens/" target="_blank">Dr. Arjan Meddens</a>, School of the Environment, Washington State University, Pullman, WA  

Responsibilities: 
* conduct collaborative research to develop machine learning image classification algorithms (RF, MLC, NN) that assess forest mortality using high-resolution satellite imagery
* assist field crew with forest inventory data collection (FIA-based)
* create and maintain spatial databases; perform logistics mapping 
* execute drone imagery acquisition missions

<br>

**Collaborative Researcher**, UAV-based rangeland project  
<br>
Principle investigator: <a href = "https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiwoNLW6438AhVZI0QIHfYgAlYQFnoECAYQAQ&url=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fgeorgia-harrison-3b709210a&usg=AOvVaw3d3NBEKO3kqVgopCBGMr5b&cshid=1671733498993523" target="_blank">Georgia Harrison</a>   
Faculty advisor: <a href = "https://www.uidaho.edu/cnr/faculty/karl" target="_blank">Dr. Jason Karl</a>
<br>
Project title: *A comparison and development of methods for estimating sagebrush shrub volume.*  
Journal article: [![Static Badge](https://img.shields.io/badge/DOI%3A%20-https%3A%2F%2Fdoi.org%2F10.1002%2Fecs2.4877-blue?style=flat)](https://doi.org/10.1002/ecs2.4877)  
Project description: This project is funded by the Joint Fire Science Program's <a href = "https://www.firescience.gov/JFSP_funding_announcements.cfm" target="_blank">Graduate Research and Innovation (GRIN) Fellowship</a> secured by PI Georgia Harrison, Department of Plant Sciences, University of Idaho and is a part of her PhD dissertation.  

Responsibilities:  
* develop workflow of estimating shrub canopy volume with 3D data from drones by modifying currently available forestry-based remote sensing tools and techniques
* use Git and [GitHub](#DroneShrub) for collaborative code sharing. GitHub repository URL: [https://github.com/gharrison159/UAVShrubVolume](https://github.com/gharrison159/UAVShrubVolume)

Here is an interactive preview of the shurb delineation and segmentation on a subset of the data for this project:

> *Use the left mouse button to tilt the 3D model and the mouse scroll wheel to zoom in and out. Individual colors represent segmented shrub.* 

<iframe src="/files/shrub_las_Widget.html" width="100%" height="600"></iframe>

<hr>


## GitHub Repositories 

<h3 id="DroneShrub">Drone shrub volume project</h3>

* Pricipal investigator: <a href = "https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiwoNLW6438AhVZI0QIHfYgAlYQFnoECAYQAQ&url=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fgeorgia-harrison-3b709210a&usg=AOvVaw3d3NBEKO3kqVgopCBGMr5b&cshid=1671733498993523" target="_blank">Georgia Harrison</a>. 
* GitHub: [![Static Badge](https://img.shields.io/badge/GitHub-https%3A%2F%2Fgithub.com%2Fgharrison159%2FUAVShrubVolume-blue?logo=github)](https://github.com/gharrison159/UAVShrubVolume)

* Zenodo: [![DOI](https://zenodo.org/badge/553770123.svg)](https://zenodo.org/doi/10.5281/zenodo.10309158) 

<h3 id="DroneTopkill"> Point cloud classification and top-kill assessment </h3>

* Principle investigator: Abhinav Shrestha  
* GitHub: [![Static Badge](https://img.shields.io/badge/GitHub-https%3A%2F%2Fgithub.com%2Fabhinavshrestha-41%2FDrone_PointCloudClassification_Topkill?logo=github&color=blue)](https://github.com/abhinavshrestha-41/Drone_PointCloudClassification_Topkill)






### University of Idaho R-Programming course (ENVS 511)

* Course GitHub repository (`MAIN`): [![Static Badge](https://img.shields.io/badge/GitHub-MAIN-blue?logo=github)](https://github.com/abhinavshrestha-41/ENVS511_R_Programming_Course_UIdaho)

* Final project repository: [![Static Badge](https://img.shields.io/badge/GitHub-FinalProject-blue?logo=github)](https://github.com/abhinavshrestha-41/ENVS511_R_Programming_Course_UIdaho/tree/main/FinalProject)
  * Website URL: [https://rpubs.com/abhinav-shrestha/979241](https://rpubs.com/abhinav-shrestha/979241)

* R-Shiny web app repository (online dashboard; click image below to visit): [![Static Badge](https://img.shields.io/badge/GitHub-RShinyApp-blue?logo=github)](https://github.com/abhinavshrestha-41/ENVS511_R_Programming_Course_UIdaho/tree/main/RShiny_App)
> [![image](https://user-images.githubusercontent.com/116584687/224510962-ee9040d6-591f-4c4e-b802-119e868d5ff2.png)](https://abhinavshrestha.shinyapps.io/Assignment15_ShinyApp/)



<hr>

# Previous Research 

### GIS-based study of topographical preference of common tree species in Palisades-Kepler State Park, IA 
(*Senior Honors Thesis, Coe College, Cedar Rapids, IA, 2019*)

Abstract: 
The study seeks to develop an understanding of the topographic characteristics that influence tree species composition of upland forests at Palisades-Kepler State Park, Linn County, Iowa. The role of Quercus alba, white oak, is a focus of this study. 123 plots containing 706 trees were sampled with the use of GPS receivers and field methods in the summer of 2017. The sampled field data were combined with its respective GPS data, and mapped on Digital Elevation Model imagery. Geographic Information System (GIS) analyses are used to develop a model of sites suitable for oak regeneration and maintenance within this forest.

Research blog URL: <a href = "https://oaksatpalisades.home.blog/" target="_blank">https://oaksatpalisades.home.blog/</a>

Thesis info URL: <a href = "https://coecollege.on.worldcat.org/oclc/1137317800" target="_blank"> https://coecollege.on.worldcat.org/oclc/1137317800 </a>

### Distribution of Oaks (Quercus spp.) in Forests of Palisades-Kepler Park, Linn County, Iowa 
(*Poster Presentation, Coe College Student Research Symposium, Cedar Rapids, IA, 2018*)

<iframe src="/files/poster.pdf" width="100%" height="800px" marginwidth="0"> </iframe>
<hr>
