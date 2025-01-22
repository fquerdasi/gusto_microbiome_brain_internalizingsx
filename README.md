# gusto_microbiome_brain_internalizingsx
Analysis scripts used for the manuscript "Childhood gut microbiome is linked to mental health at school age via the functional connectome"

Preprint can be found at: https://osf.io/preprints/psyarxiv/u9dw5 

## System Requirements
This code has been tested on a MacBook Pro with MacOS Sequioa 15.01, running R version 4.2.3 in RStudio version 2022.07.2.   

**Required packages include:**   
attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] corrplot_0.92      patchwork_1.2.0    sjPlot_2.8.14      rstatix_0.7.2      Hmisc_5.1-0        mosaic_1.8.4.2    
 [7] mosaicData_0.20.3  ggformula_0.10.4   compositions_2.0-6 vegan_2.6-4        permute_0.9-7      readxl_1.4.2      
[13] mixOmics_6.23.4    lattice_0.21-8     MASS_7.3-60        lubridate_1.9.2    forcats_1.0.0      stringr_1.5.0     
[19] dplyr_1.1.2        purrr_1.0.1        readr_2.1.4        tidyr_1.3.0        tibble_3.2.1       ggplot2_3.4.2     
[25] tidyverse_2.0.0    lmerTest_3.1-3     lme4_1.1-33        Matrix_1.5-4.1   

The only non-standard software is the PROCESS macro for R. Instructions for installing and loading it are below. 

## Installation Guide  
To install R, go here: [Windows](https://cran.r-project.org/bin/windows/base/old/) or [Mac](https://cran.r-project.org/bin/macosx/)  
To install RStudio, follow instructions [here](https://posit.co/download/rstudio-desktop/)  
Each of these installations should take a few minutes.   

To install the required packages, you can run the following code (should take around 5 minutes):
```
install.packages(c("tidyverse", "MixOmics", "readxl", "vegan", "compositions", "mosaic", "Hmisc", "rstatix", "sjPlot", "patchwork", "corrplot", "MASS", "ggplot2"))
```
The mediation models in this code use the PROCESS macro for R. You can download the it [here](https://haskayne.ucalgary.ca/CCRAM/resource-hub). Once downloaded, open the folder, go to the subfolder "PROCESS v4.3 for R", open the script "process.R" and run it through in its entirety (without changing anything) to load the process function. 

## Demo Instructions 
coming soon
