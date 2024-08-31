This is the submission of Summer project by 491916. please DO NOT move any data. 

Contents: 
"491916_summer_project_data_analysis.Rmd" is the R markdown format, data analysis script, which contains the scipts of analysis for that of the summer project. 
The datasets, orginally encoded as "warfarin_ppi.dta", "doac_ppi.dta","aurum_hes_gi_bleed_dx.dta", "aurum_gi_bleed_dx.dta", are not to be shared per the data sharing protocol. 

Running the script: 
therotically, the script is in the R markdown format, by pressing running all blocks below, the script should start running and produce all the materials required for the analysis. 
but since the the datasets and the code lists are not to be shared per the data sharing agreement, such a option is not available. 

PLease ensure the following requirment and dependencies are present: 

R version 4.3.2

library(here)

library(haven)

library(lubridate)

library(tableone) 

library(ggplot2)

library(survival)

library(survminer)

library(parallel)

library(doParallel)

library(timereg)

library(matrixStats) 

library(tidysmd)

library(cobalt)

library(multcomp)

library(dplyr)
