This is the submission of Summer project by 491916. please DO NOT move any data. 

Contents: 
"data_analysis.Rmd" is the R markdown format, data analysis script, which contains the scipts of analysis for that of the summer project. 
"data_analysis.csv" is a csv file containing the the codelists for diaganosises for gastrointestinal bleeding. 
The datasets, orginally encoded as "warfarin_ppi.dta", "doac_ppi.dta","aurum_hes_gi_bleed_dx.dta", "aurum_gi_bleed_dx.dta", are not to be shared per the data sharing protocol. 

Running the script: 
therotically, the R is in the R markdown format, the by pressing running all blocks below, the script should start running and produce all the materials required for the analysis. 
but since the the datasets are not to be shares, such a option is not available. 

Requirment and dependencies: 
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
