<img src="Logo/photo_5816681274650247274_x.jpg" align="center" alt="Holistic-WDS-Risk">

**HOLISTIC ASSESSMENT OF SOCIAL, ENVIRONMENTAL AND ECONOMIC IMPACTS OF PIPE BREAKS: A CASE STUDY OF VANCOUVER**


# Overview

This study presents a holistic assessment framework for water pipe break impacts in Vancouver, Canada. It assesses social, environmental, and economic vulnerabilities as a consequence of failure (COF), combining them with the probabilities of failure (POF) is evaluated by a Weibull model. Combining these criteria prioritizes pipe replacement and rehabilitation to mitigate the adverse impacts of infrastructure failure.


- This repository contains the codes and data used for the research project. 

- The codes was developed using **Jupyter Notebook** for data analysis and visualization.



# File Structure

This study is organized in Jupyter Notebook as follows:

- **[Data](Data)**
  
  This directory contains:
  - [Data-Cleaning.ipynb](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/8e6f95337191c92b9653fb64e1c0c43cf6c35ebe/Data/Data-Cleaning.ipynb): This code is used specificly for cleaning the data of Vancouver and making Correlation matrix.
  - [Variable in DAs.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/3992b2d9518029f91f903e29e3410e1bb0a2cb86/Data/Variable%20in%20DAs.csv): The 2021 Census of Population data of Vancouver City in each dissemination area (DA) was used as the input file for Data-Cleaning.

- **[PCA(principal-component-analysis)](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/863c58878996d9f04cc1f30be4c272d5e2745962/PCA(principal-component-analysis))**

  This directory contains:
  - [PCA.ipynb](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/3992b2d9518029f91f903e29e3410e1bb0a2cb86/PCA(principal-component-analysis)/PCA.ipynb): This code is used to apply the Principal Component Analysis (PCA) method on the dataset. The PCA code is responsible for dimensionality 
    reduction and any related data transformations.
  - [Selected_variables.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/3992b2d9518029f91f903e29e3410e1bb0a2cb86/PCA(principal-component-analysis)/Selected_variables.csv): This file is the output of the data cleaning code which contains the final variables in each dissemination areas (DAs) of Vancouver, and this file is used as the input of the PCA method.

- **[Consequences Of Failure(COF)](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/f3b78f851c7c52dfdbead12e57493b4a4ab3f09a/Consequences%20Of%20Failure(COF))**

  This directory contains:
  - [COF(SVCI).ipynb](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/COF%20(SVCI).ipynb): This code is used to make social, environmental, and economic vulnerability indices and creating their maps.
  - [scaled_df.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/scaled_df.csv): This file is one of the output results of the PCA code, which contains the scaled final variables. It is used for calculating the social vulnerability index(SVI). 
  -  [result_df.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/result_df.csv): This file is also one of the output results of the PCA code that consist of the weight of each final variables. It is used for calculating the social vulnerability index(SVI). 
  -   [SVI-map.geojson](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/SVI-map.geojson): This geojson file is used for generating the social vulnerability index map in DAs. This file is created by QGIS.
  - [parks_floodplain_area.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/parks_floodplain_area.csv): This file was extracted from QGIS by using the shapefile of park and floodplain areas in each DAs in Vancouver City. This file is used for calculating the environmental vulnerability index (EVI).
  -   [EVI.geojson](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/EVI.geojson):  This geojson file is used for generating the EVI map in DAs. This file is created by QGIS.
  - [Cost_Analysis_Catalogue&main.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/Cost_Analysis_Catalogue%26main.csv): This file is extracted from The RSMeans heavy construction catalogue for calculating the cost analysis for water distribution system of Vancouver City. This file is used for calculating the economic vulnerability index (ECI).
  -  [WMAIN-120M.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/WMAIN-120M.csv): This is the inventory file of the water distribution system of Vancouver City. This file is used for calculating the ECI.
  -    [ECI-120M.geojson](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/ECI-120M.geojson): This geojson file is used for generating the ECI map of pipes. This file is created by QGIS.
 
- **[Probability Of Failure (POF) & Risk](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/1e921571d8825be532da104dc03da70bcaa505b4/Probability%20Of%20Failure%20(POF)%20%26%20Risk)**
 
  This directory contains:
  -  [POF & Risk.ipynb](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Probability%20Of%20Failure%20(POF)%20%26%20Risk/POF%20%26%20Risk.ipynb): This code makes a Weibull distribution and Risk framework.
  -  [SVCI-Aggr.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Probability%20Of%20Failure%20(POF)%20%26%20Risk/SVCI-Aggr.csv): This is the required input file to calculate POF and Risk.
  -  [Risk-120M.geojson](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Probability%20Of%20Failure%20(POF)%20%26%20Risk/Risk-120M.geojson): The input geojson file to generate POF and Risk map.

# Requirements

[Python version 3.11](https://www.python.org/downloads/release/python-3110/) was used to all codes.

There is a list of requirements dependencies for this study's Python codes [here](requirements.txt).


# Cite Us

    @article{doi:  ,
    author = {Armine Sinaei, Rebecca Dziedzic, and Enrico Creaco },
    title = {HOLISTIC ASSESSMENT OF SOCIAL, ENVIRONMENTAL AND ECONOMIC IMPACTS OF PIPE BREAKS: A CASE STUDY OF VANCOUVER},
    journal = {Journal of Water Resources Planning and Management},
    volume = {149},
    number = { },
    pages = { }, 
    year = {2023},
    doi = { },
    URL = { }, 
    }
    
# Contact
-------
Armine Sinaei - seyedeharmineh.sinaei01@universitadipavia.it; arminesinaei@gmail.com

Rebecca Dziedzic - rebecca.dziedzic@concordia.ca

Enrico Creaco - creaco@unipv.it

