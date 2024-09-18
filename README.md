![](logo.png)

# SCCS-NY 2024 Workshop 

## Interactive, reproducible, and accessible species distribution modeling for conservation with Wallace

# Organizers

-   Andrew Gaier, Grad Center-CUNY (agaier@gradcenter.cuny.edu)
-   Daniel F. López-Lozano, CBC-AMNH (dlopezlozano@amnh.org)
-   Bethany A. Johnson, CBC-AMNH (wallaceecomod@gmail.com)

# Logistics

-   Date: Wednesday, October 9rd
-   Time: 1:00 - 3:00 PM EDT
-   Location: TBD

# Description

Species distribution modeling (SDM) is an important tool for conservation scientists, as it enables us to estimate present species range limits and make predictions about ranges for other areas and time periods. Advances in model-building and evaluation theory are common in the ecology and evolution literature. However, most cutting-edge methods are only accessible to those scientists who can read and write computer code, which results in a 'barrier to use' for many potential users. The Wallace ecological modeling application, implemented in the R programming language as the CRAN package `wallace`, provides a graphical user interface allowing any user to implement advanced SDM methods. Additionally, Wallace provides extensive guidance text and references key papers from the literature to help both new and experienced users learn best practices. Each model-building session can be exported as a fully documented R Markdown script file, to ensure reproducibility, ease of reporting, and for more advanced users, an easily modifiable code that extends Wallace's functionality. In this workshop, we will go through the basics of SDM using Wallace. We will demonstrate the key features of the modular software, show applications to conservation science, and specifically the utility of SDM outputs for formal IUCN assessments.

# Workshop Schedule

-   1:00 -- 1:10: Who we are & why we are here
-   1:10 -- 1:40: Introduction to species distribution modeling
-   1:40 -- 2:00: Introduction to R and Wallace
-   2:00 -- 2:10: Break / troubleshooting
-   2:10 -- 2:30: Wallace v2 live demo and walkthrough
-   2:30 -- 2:45: Using Wallace v2 with your own data
-   2:45 -- 3:00: Preview of new v3 features for conservation

# Pre- & Post- Workshop Surveys

Please take the pre- and post-workshop surveys. They really help us!

-   Before the workshop: <a href="https://forms.gle/EzWNJmJp1oGM9W3y8" target="_blank">Pre-workshop survey</a>

-   After the workshop: <a href="https://forms.gle/2J8bXkQrBNw3x6ds8" target="_blank">Post-workshop survey</a>

# Getting started

*Please install R and Wallace prior to this Workshop. Downloading Wallace in R can take a while depending on your computer.*

1.  Install R (version ≥ v.3.5.0) Download for <a href="https://cran.r-project.org/bin/windows/base/" target="_blank">Windows</a> or <a href="https://cran.r-project.org/bin/macosx/" target="_blank">Mac</a> We also recommend downloading <a href="https://www.rstudio.com/products/rstudio/download/#download" target="_blank">Rstudio</a>, which makes running R visually easier.\
    Alternatively, you can use <a href="https://rstudio.cloud/" target="_blank">Rstudio cloud</a> with a Google or Github account.

2.  Install the 'wallace' package from CRAN or Github (version \#)

    -   Open Rstudio.
    -   Enter the following code into the terminal and hit Run.
This may take a several minutes.  

From CRAN...
```
install.packages("wallace")  
library(wallace)  
run_wallace()  
```

From Github...
```
install.packages("devtools")  
devtools::install_github("wallaceecomod/wallace@master")  
library(wallace)  
run_wallace()  
```

# Data for workshop
During the workshop, we will allow you to choose your own species to work with during the demo portion. However, in the event of internet connectivity issues or issues with GBIF during the workshop, we have included a dataset you can work with here.

<a href="https://drive.google.com/drive/folders/1oqBpCfFLlUUAMtg_63JUX5jpfGgdnw20?usp=sharing" target="_blank">Canned Data</a>  
Includes:  
- Occurrence data for two species  
- Environmmental data at 2.5arcmin resolution  
- a binary SDM  
- a shapefile of Colombia  

# Wallace Specific Resources

-   <a href="https://wallaceecomod.github.io/" target="_blank">Wallace homepage</a>
-   <a href="https://wallaceecomod.github.io/wallace/articles/tutorial-v2.html" target="_blank">Link to Wallace How-to Vignette</a>

# Issues

If you encounter a bug while using Wallace, you can report it here <a href="https://forms.gle/QWbPup6FxNZTqzjY6" target="_blank">Bug Reporting Form</a>


