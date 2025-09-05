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
  • caret: 7.0.1
  • dismo: 1.3.16
  • dplyr: 1.1.4
  • emmeans: 1.10.4
  • ggdist: 3.3.2
  • ggplot2: 3.5.2
  • ggrepel: 0.9.6
  • janitor: 2.2.1
  • maxnet: 0.1.4
  • nnet: 7.3.19
  • patchwork: 1.3.0
  • pROC: 1.18.5
  • purrr: 1.0.2
  • raster: 3.6.30
  • readxl: 1.4.3
  • scales: 1.3.0
  • sf: 1.0.19
  • terra: 1.8.5
  • tibble: 3.2.1
  • tidyr: 1.3.1
  • usdm: 2.1.7
  • viridis: 0.6.5

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
