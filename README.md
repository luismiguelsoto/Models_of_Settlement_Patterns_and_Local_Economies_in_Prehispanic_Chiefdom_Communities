Models of Settlement Patterns and Local Economies in Prehispanic Chiefdom Communities of the Sierra Nevada de Santa Marta, Colombia
--------------------------------------------------------------

This repository contains the R code and data used to model the settlement patterns of Tairona chiefdoms in the Sierra Nevada de Santa Marta, Colombia. The script uses predictive modeling to analyze how environmental factors influenced settlement locations and, in turn, shaped local economies and social organization.

Repository Structure:
----------------------------------
1. Database:
   - Contains the Excel files with the datasets used in the analysis:
     • FUNCTIONAL_CERMICS_TAIRONA_UNTIL_2025.xlsx

2. GIS:
   - Contains the spatial data files (shapefile components) defining the study area:
     • STRUCTURES_UNTIL_2025.shp
     • STRUCTURES_UNTIL_2025.dbf
     • STRUCTURES_UNTIL_2025.shx
     • STRUCTURES_UNTIL_2025.prj
     • STRUCTURES_UNTIL_2025.cpg

3. R Code Files:
   - The main R script (or R Markdown file) contains the code to:
     a) Load required packages.
     b) Download the Excel datasets and GIS files directly from GitHub.
     c) Process the data, build similarity matrices, calculate centrality metrics, and perform network analysis.
     d) Generate the figures and tables as presented in the manuscript.

Software and Key Package Versions:
----------------------------------
- R version: [R 4.4.1]
- Key R packages used in this project include (with version numbers):
  • sf: e.g., version 1.0-0 (built under R 4.4.2; linking to GEOS 3.12.2, GDAL 3.9.3, PROJ 9.4.1) - installed 1.0.19 
  • spdep: (built under R 4.4.2) - installed 1.3.7 
  • ggplot2: e.g., version 3.3.6 - installed 3.5.1 
  • viridis: installed 0.6.5 
  • car: installed 3.1.3 
  • spatstat.explore: e.g., version 3.3-2 - installed 3.3.2 
  • spatstat.geom: e.g., version 3.3-3 - installed 3.3.3 
  • spatstat.model: e.g., version 3.3-2 - installed 3.3.2 
  • network: installed version 1.18.2 (update available: 1.19.0) - installed 1.18.2 
  • ggspatial: (built under R 4.4.2) - installed 1.1.9 
  • vegan: e.g., version 2.6-8 - installed 2.6.8 
  • scales: installed 1.3.0 
  • dplyr: installed 1.1.4 
  • patchwork: installed 1.3.0 
  • tidygraph: installed 1.3.1 
  • ggraph: installed 2.2.1 
  • GGally: installed 2.2.1 
  • FSA: e.g., version 0.9.5 - installed 0.9.5 
  • stats: - installed 4.4.1 
  • ggpubr: installed 0.6.0 
  • writexl: installed 1.5.1 
  • openxlsx: installed 4.2.7.1 
  • sna: e.g., version 2.8 (created on 2024-09-07) - installed 2.8 
  • statnet: e.g., version 2019.6 (2019-06-13) - installed 2019.6 
  • igraph: installed 2.0.3 
  • DT: installed 0.33 
  • tnet: installed 3.0.16 
  • kableExtra: installed 1.4.0 
  • readxl: installed 1.4.3 
  • dunn.test: installed 1.3.6 
  • ggdist: installed 3.3.2 

Getting Started:
----------------------------------
1. Clone or download this repository.
2. Open the main R script (or R Markdown file) in RStudio.
3. Ensure that you have an active Internet connection; the code downloads the Excel and GIS files directly from GitHub.
4. Run the R script from top to bottom to reproduce the analysis and generate all figures and tables as presented in the manuscript.
5. For any issues, consult the comments in the syntax or contact the corresponding author.

Manuscript Summary:
----------------------------------
This article investigates how environmental and social factors influenced the settlement patterns of Tairona communities (10th–16th centuries AD) in the El Congo and La Aguja microbasins, located in the southwestern foothills of the Sierra Nevada de Santa Marta. The analysis is based on systematic archaeological studies covering an area of approximately 40 km², carried out within the Regional Archaeology Program of the Río Frío basin. Predictive models were used to estimate the potential distribution of human occupation and to identify the key variables that explain where and why settlements were established and maintained. The results show that structural slopes, proximity to water sources, and access to fertile agricultural soils played a central role in determining residential spacing and population density, which were crucial for shaping local economies. These settlement patterns fostered productive differentiation and varying degrees of economic integration, which led to frequent interactions between households and communities. In turn, these dynamics may have facilitated the emergence of social segments capable of mobilizing resources, laying the foundations for the development of complex decision-making structures and the formation of hierarchical forms of social organization, such as chiefdoms.

For questions or further information, please contact:
lms313@pitt.edu
