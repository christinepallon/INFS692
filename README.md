# **INFS692 // Data Science // Final Project**

## by Christine Pallon

***


## Welcome!


This GitHub repository contains all the files related to my Data Science (INFS 692) final project for Winter 2022.  

The contents are as follows:

1. ReadMe
2. Model 1 .RMD
3. Model 1 .PDF
4. Model 2 .RMD
5. Model 2 .PDF 
6. Model 3 .RMD
7. Model 3 .PDF 

***

## Model details

All models use the **radiomics_completedata.csv** dataset, with *Failure.binary* as the property we're trying to predict. As such, all models deal with binary classification. All models also use an 80/20 training/testing split. 

Our three models are as follows:

**Model 1**: An ensemble classification model with the following base learners: RF, XGBoost, and GBM.

**Model 2**: A neural network-based classification model.

**Model 3**: A comparison between three clustering methods: K-Means, hierarchical, and model-based clustering. 

*** 

## Set-up

To run the code in the .RMD files yourself, make sure to have R installed on your machine and RStudio set up.

***

## Packages used

Beyond base R, this project uses a variety of packages to prepare, build, and assess the models. The packages used in each model can be found at the top .RMD file for each model, but the entire list of packages used can be found below:

`library(dplyr)`     
`library(rsample)`    
`library(recipes)`    
`library(purrr)`     
`library(tidyverse)`  
`library(pROC)`  
`library(keras)`       
`library(tfruns)`       
`library(tfestimators)`  
`library(tensorflow)`   
`library(h2o)`    
`library(vip)`  
`library(ggplot2)`  
`library(stringr)`     
`library(gridExtra)`  
`library(cluster)`   
`library(factoextra)`  
`library(mclust)`  
`library(flexclust)`

## Further considerations

Windows users should be aware that one of the functions used in **Model 1** to build our XGBoost base learner, `h2o.xgboost()`, is currently not supported on Windows machines.

Certain models may take quite a long time and use up a lot of memory to run. This is expected.


## Contact

If you  have any questions about this project or have any issues, contact me at christine.pallon@mail.mcgill.ca

*Happy classifying!* 
