# Replication Data for: The Effect of Distrust on Government Stringency During the Covid-19 Pandemic
This document outlines the structure of the replication data.

The rmarkdown file used to create the final paper is: insert here , this file also contains the code used in the analysis.

That files uses functions defined in the functions folder, which are accessed using the `box` pacakge. functions/ts are general functions used in the paper and functions/ap are functions used to assess the statistical assumptions. Not all functions that are defined were used in the final paper. \
\
Functions imported from other packages are also imported using the `box` package. Here is complete list of packages used and required for the replication code to run: 
- box (for importing functions without clustering namespace)
- dplyr (for data manipulation)
- forcats (helps create plots with ordered labels)
- ggplot2 (for creating plots)
- lme4 (main pacakge used for creating random effects models)
- texreg (for creating regression tables)
- sandwich (for clustered standard errors)
- lmtest (same as above)
- lubridate (for date manipulation)
- magrittr (for pipe operator)
- readr (importing data)
- broom (tidying models)
- kableExtra (for producing tables)
- knitr (used for rmarkdown)
- sf (used in creating of map)
- ggsci (for graph colouring)
- car (for calculation of variance inflation factors)
- HLMdiag (for calculation of residuals)
- influence.ME (for calculation of DFBETAS)

panel_data.Rdata is the file containing the replication data, the function `load_project_data()` transforms some of the columns to create the dataframe used in the analysis. panel_data.csv is a file containing a csv copy of this same data (including the transformations applied by `load_project_data()`.
