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

- **[[PCA(principal-component-analysis)](https://github.com/arminesinaei/SEE-PipeBreaks/tree/c85fc9455ec32b0af550783e9245ac3418bf35ca/PCA(principal-component-analysis))](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/f3b78f851c7c52dfdbead12e57493b4a4ab3f09a/PCA(principal-component-analysis))**

  This directory contains:
  - PCA.ipynb: This code is used to apply the Principal Component Analysis (PCA) method on the dataset. The PCA code is responsible for dimensionality 
    reduction and any related data transformations.
  - Selected_variables.csv: This is the input of PCA method.

- **[[Consequences Of Failure(COF)](https://github.com/arminesinaei/SEE-PipeBreaks/tree/efa55492ce349a52169870327737bb11b33f2848/Consequences%20Of%20Failure(COF))](https://github.com/UrbanLinks/Holistic-WDS-Risk/tree/f3b78f851c7c52dfdbead12e57493b4a4ab3f09a/Consequences%20Of%20Failure(COF))**

  This directory contains:
  - COF(SVCI).ipynb: This code is used to make social, environmental, and economic vulnerability indices and creating their maps.
  - scaled_df.csv, result_df.csv, SVI-map.geojson: The input files for obtaining the social vulnerability index and generating its map.
  - parks_floodplain_area.csv, EVI.geojson:
  - Cost_Analysis_Catalogue&main.csv, WMAIN-120M.csv, ECI-120M:

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

