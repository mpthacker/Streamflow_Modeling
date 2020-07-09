# Streamflow_Modeling
Personal project modeling USGS stream data. Particularly from a Bayesian hierarchal perspective. This project is an attempt to gain a fuller understanding of Bayesian hierarchal modeling in general by applying the concepts to streamflow data from USGS stream gages. Initially, only gages in the Merrimack river watershed have been chosen to limit size of the dataset. See the Table of Contents below for more detailed descriptions of every file in the repository. 


# Table of Contents

## in_prog.txt 
List of models or aspects of the project currently being worked on

## to_do.txt
List of models or aspects of the project intended for future work. Not necessarily ordered

## DataManipDFL.rmd
Read in data for stream gages, calculate and extract relevant variables aggregated on a monthly scale, export to files in data folder. Discusses choice of variables calculated

## DataManipDFLseasonal.rmd
As for DataManipDFL.rmd but aggregated seasonally

## DataManipPRCP.rmd 
Read in data for weather stations, calculate and extract relevant variables, export files to data folder. Discussed choice of variables calculated

## NormMeanMod.rmd
Fit models with unbounded normal data model. Discusses the theoretical issues with this approach and lack of support from the data

## TruncNormMeanMod.rmd 
Fit models with truncated normal data model. More appropriate for a strictly postive variable of interest

## Gen_Data
Folder with most necessary files and shp_links.txt file containing links to where shapefiles may be downloaded from due to github storage limits
