Network Analysis in Tairona Chiefdoms of the Río Frío Basin
--------------------------------------------------------------

This repository contains the R code and data used to analyze the interaction networks in the Tairona chiefdom communities of the Río Frío Basin (Sierra Nevada de Santa Marta, Colombia). The goal of the study is to investigate settlement patterns and scales of sociopolitical interaction and economic integration over time, using network analysis applied to ceramic artifact assemblages.

Repository Structure:
----------------------------------
1. Database/
   - Contains the Excel files with the datasets used in the analysis:
     • Buritaca_Desgrasantes.xlsx
     • Buritaca_Desgrasantes_attr.xlsx
     • Buritaca_Tipos.xlsx
     • Buritaca_Tipos_attr.xlsx
     • Neguanje_Desgrasantes.xlsx
     • Neguanje_Desgrasantes_attr.xlsx
     • Neguanje_Tipos.xlsx
     • Neguanje_Tipos_attr.xlsx
     • Tairona_Desgrasantes.xlsx
     • Tairona_Desgrasantes_attr.xlsx
     • Tairona_Tipos.xlsx
     • Tairona_Tipos_attr.xlsx

2. GIS/
   - Contains the spatial data files (shapefile components) defining the study area:
     • POLYGON_SURVEY_UNTILL_2023.shp
     • POLYGON_SURVEY_UNTILL_2023.dbf
     • POLYGON_SURVEY_UNTILL_2023.shx
     • POLYGON_SURVEY_UNTILL_2023.prj
     • POLYGON_SURVEY_UNTILL_2023.cpg

3. R Code Files
   - The main R script (or R Markdown file) contains the code to:
     a) Load required packages.
     b) Download the Excel datasets and GIS files directly from GitHub.
     c) Process the data, build similarity matrices, calculate centrality metrics, and perform network analysis.
     d) Generate the figures and tables as presented in the manuscript.

Software and Key Package Versions:
----------------------------------
- R version: [R 4.4.1]
- Key R packages used in this project include (with version numbers):
    •  sf: e.g., version 1.0-0 (built under R 4.4.2; linking to GEOS 3.12.2, GDAL 3.9.3, PROJ 9.4.1)
    •  spdep: (built under R 4.4.2)
    •  ggplot2: e.g., version 3.3.6
    •  viridis: (version as provided by CRAN)
    •  car: (version as provided by CRAN)
    •  spatstat.explore: e.g., version 3.3-2
    •  spatstat.geom: e.g., version 3.3-3
    •  spatstat.model: e.g., version 3.3-2
    •  network: installed version 1.18.2 (update available: 1.19.0)
    •  ggspatial: (built under R 4.4.2)
    •  vegan: e.g., version 2.6-8
    •  scales: (version as provided by CRAN)
    •  dplyr: (version as provided by CRAN)
    •  patchwork: (version as provided by CRAN)
    •  tidygraph: (version as provided by CRAN)
    •  ggraph: (version as provided by CRAN)
    •  GGally: (version as provided by CRAN)
    •  FSA: e.g., version 0.9.5
    •  ggpubr: (version as provided by CRAN)
    •  writexl: (version as provided by CRAN)
    •  openxlsx: (version as provided by CRAN)
    •  sna: e.g., version 2.8 (created on 2024-09-07)
    •  statnet: e.g., version 2019.6 (2019-06-13)
    •  igraph: (version as provided by CRAN)
    •  DT: (version as provided by CRAN)
    •  tnet: (version as provided by CRAN)
    •  kableExtra: (version as provided by CRAN)
    •  readxl: (version as provided by CRAN)
    •  dunn.test: (version as provided by CRAN)

Getting Started:
----------------------------------
1. Clone or download this repository.
2. Open the main R script (or R Markdown file) in RStudio.
3. Ensure that you have an active Internet connection; the code downloads the Excel and GIS files directly from GitHub.
4. Run the R script from top to bottom to reproduce the analysis and generate all figures and tables as presented in the manuscript.
5. For any issues, consult the comments in the code or contact the corresponding author.

Manuscript Summary:
----------------------------------
This article analyzes the interaction networks in the Tairona chiefdom communities of the Sierra Nevada de Santa Marta, Colombia, to investigate settlement patterns and scales of sociopolitical interaction and economic integration over time. The study uses network analysis applied to technological and typological attributes of ceramic artifact assemblages from pre-Hispanic residential areas. The results indicate that certain settlements played central roles in the network, acting as intermediaries in the distribution of ceramic goods and possibly in socio-political coordination. These findings underscore the complexity of social and economic relationships in pre-Columbian societies and have direct implications for understanding settlement patterns and sociopolitical centralization in the Tairona chiefdoms.

For questions or further information, please contact:
lms313@pitt.edu
