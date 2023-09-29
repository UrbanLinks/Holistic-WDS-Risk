A holistic assessment framework for the impacts of water distribution pipe breaks

Case study: Vancouver City

# Overview

This study presents a holistic assessment framework for water pipe break impacts in Vancouver, Canada. It assesses social, environmental, and economic vulnerabilities as a consequence of failure (COF), combining them with the probabilities of failure (POF) is evaluated by a Weibull model. Combining these criteria prioritizes pipe replacement and rehabilitation to mitigate the adverse impacts of infrastructure failure.


- This repository contains the code and data used for the research project. 

- The codes was developed using Jupyter Notebook for data analysis and visualization.



# File Structure

This study is organized in Jupyter Notebook as follows:

- **[Data](Data)**
  
  This directory contains:
  - Data-Cleaning.ipynb: This code is used specificly for cleaning the data of Vancouver and making Correlation matrix.
  - Variable in DAs.csv: The dataset in dissemination areas of Vancouver City which is the input of Data-Cleaning.

- **[PCA(principal-component-analysis)](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/863c58878996d9f04cc1f30be4c272d5e2745962/PCA(principal-component-analysis))**

  This directory contains:
  - PCA.ipynb: This code is used to apply the Principal Component Analysis (PCA) method on the dataset. The PCA code is responsible for dimensionality 
    reduction and any related data transformations.
  - Selected_variables.csv: This is the input of PCA method.

- **[Consequences Of Failure(COF)](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/f3b78f851c7c52dfdbead12e57493b4a4ab3f09a/Consequences%20Of%20Failure(COF))**

  This directory contains:
  - COF(SVCI).ipynb: This code is used to make social, environmental, and economic vulnerability indices and creating their maps.
  - scaled_df.csv, result_df.csv, SVI-map.geojson: The input files for obtaining the social vulnerability index and generating its map.
  - parks_floodplain_area.csv, EVI.geojson: The input files for obtaining the environmental vulnerability index and generating its map.
  - Cost_Analysis_Catalogue&main.csv, WMAIN-120M.csv, ECI-120M.geojson: The input files for obtaining the economic vulnerability index and generating its map
 
  - **[Probability Of Failure (POF) & Risk](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/1e921571d8825be532da104dc03da70bcaa505b4/Probability%20Of%20Failure%20(POF)%20%26%20Risk)**
 
  This directory contains:
  -  POF & Risk.ipynb: This code makes a Weibull distribution and Risk framework.
  -  SVCI-Aggr.csv: This is the required input file to calculate POF and Risk.
  -  Risk-120M.geojson: The input geojson file to generate POF and Risk map.

# Requirements

There is a list of requirements dependencies for this study's Python codes [here](requirements.txt).

# Example


# Cite Us

    @article{doi:  ,
    
    author = {Armine Sinaei, Rebecca Dziedzic,and Enrico Creaco },
    
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

