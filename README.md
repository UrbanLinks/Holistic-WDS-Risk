HOLISTIC ASSESSMENT OF SOCIAL, ENVIRONMENTAL AND ECONOMIC IMPACTS OF PIPE BREAKS: A CASE STUDY OF VANCOUVER


# Overview

This study presents a holistic assessment framework for water pipe break impacts in Vancouver, Canada. It assesses social, environmental, and economic vulnerabilities as a consequence of failure (COF), combining them with the probabilities of failure (POF) is evaluated by a Weibull model. Combining these criteria prioritizes pipe replacement and rehabilitation to mitigate the adverse impacts of infrastructure failure.


- This repository contains the code and data used for the research project. 

- The codes was developed using **Jupyter Notebook** for data analysis and visualization.



# File Structure

This study is organized in Jupyter Notebook as follows:

- **[Data](Data)**
  
  This directory contains:
  - [Data-Cleaning.ipynb](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/8e6f95337191c92b9653fb64e1c0c43cf6c35ebe/Data/Data-Cleaning.ipynb): This code is used specificly for cleaning the data of Vancouver and making Correlation matrix.
  - [Variable in DAs.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/3992b2d9518029f91f903e29e3410e1bb0a2cb86/Data/Variable%20in%20DAs.csv): The dataset in dissemination areas of Vancouver City which is the input of Data-Cleaning.

- **[PCA(principal-component-analysis)](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/863c58878996d9f04cc1f30be4c272d5e2745962/PCA(principal-component-analysis))**

  This directory contains:
  - [PCA.ipynb](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/3992b2d9518029f91f903e29e3410e1bb0a2cb86/PCA(principal-component-analysis)/PCA.ipynb): This code is used to apply the Principal Component Analysis (PCA) method on the dataset. The PCA code is responsible for dimensionality 
    reduction and any related data transformations.
  - [Selected_variables.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/3992b2d9518029f91f903e29e3410e1bb0a2cb86/PCA(principal-component-analysis)/Selected_variables.csv): This is the input of PCA method.

- **[Consequences Of Failure(COF)](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/f3b78f851c7c52dfdbead12e57493b4a4ab3f09a/Consequences%20Of%20Failure(COF))**

  This directory contains:
  - [COF(SVCI).ipynb](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/COF%20(SVCI).ipynb): This code is used to make social, environmental, and economic vulnerability indices and creating their maps.
  - [scaled_df.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/scaled_df.csv),  [result_df.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/result_df.csv),  [SVI-map.geojson](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/SVI-map.geojson): The input files for obtaining the social vulnerability index and generating its map.
  - [parks_floodplain_area.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/parks_floodplain_area.csv),  [EVI.geojson](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/EVI.geojson): The input files for obtaining the environmental vulnerability index and generating its map.
  - [Cost_Analysis_Catalogue&main.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/Cost_Analysis_Catalogue%26main.csv),  [WMAIN-120M.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/WMAIN-120M.csv),  [ECI-120M.geojson](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Consequences%20Of%20Failure(COF)/ECI-120M.geojson): The input files for obtaining the economic vulnerability index and generating its map
 
- **[Probability Of Failure (POF) & Risk](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/1e921571d8825be532da104dc03da70bcaa505b4/Probability%20Of%20Failure%20(POF)%20%26%20Risk)**
 
  This directory contains:
  -  [POF & Risk.ipynb](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Probability%20Of%20Failure%20(POF)%20%26%20Risk/POF%20%26%20Risk.ipynb): This code makes a Weibull distribution and Risk framework.
  -  [SVCI-Aggr.csv](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Probability%20Of%20Failure%20(POF)%20%26%20Risk/SVCI-Aggr.csv): This is the required input file to calculate POF and Risk.
  -  [Risk-120M.geojson](https://github.com/UrbanLinks/Holistic-WDS-Risk/blob/5412604b096ac3065b68e2c901519215a51dd35d/Probability%20Of%20Failure%20(POF)%20%26%20Risk/Risk-120M.geojson): The input geojson file to generate POF and Risk map.

# Requirements

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

