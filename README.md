# CMIP6_Climate_Projections_Script
The CMIP6 Climate Projections script is an R Markdown document that guides users in downloading and preprocessing daily and monthly averages of the global dataset variables: temperature, precipitation, and PET.

## About the CMIP6 climate projections datasets

The **Inter-Sectoral Impact Model Intercomparison Project** develops and provides climate and socioeconomic forcing datasets with a spatial resolution of 1 degree, along with historical and climate projections under SSP-RCP scenarios from 2015 to 2100. 

The datasets from the ISIMIP3b protocol provide bias-corrected CMIP6 climate forcing for historical data and SSP1-RCP2.6, SSP3-RCP7.0, and SSP5-RCP8.5 conditions. The bias adjustment corrects the simulated data based on corrected ERA5 observational data (W5E5).

More information can be found at: *https://www.isimip.org/about/*

## About the scripts

The Rmd scripts are dynamic documents that combine narrative text with code chunks, guiding the user through the code execution. Both code routines filter the server requests and download the datasets specified for the user's time window. The scripts are organized into four main steps:

1. Setting paths and directories.
2. Defining variables and the time window of interest.
3. Downloading the datasets of interest.
4. Preprocessing the NetCDF files for either a shapefile or a list of coordinates.

## About R and RStudio

**i. Download and Install**

Follow the instructions below to install R and run the R scripts.
1. R: Download and install R by following the link that corresponds to your operating system Windows, Mac, or Linux: *https://cran.r-project.org/*
2. RStudio: RStudio is an application that assists you in writing R code. You can download it from: *https://posit.co/downloads/*
Once you have both R and RStudio installed on your computer, you can begin using R by opening the RStudio program. For more information, visit: *https://rstudio-education.github.io/hopr/starting.html*

**ii. To open an R Markdown (Rmd) file in RStudio**

1. Open RStudio: Launch RStudio on your computer.
2. Open Rmd File: Once you're in RStudio, you can open an Rmd file in one of the following ways:
- File > Open File.
- Drag the Rmd file from your file explorer and drop it onto the RStudio window.
3. Run: Once the Rmd file is open, you can run the individual chunks of code by placing your cursor within the chunk and clicking the "Run" button in the toolbar or using the keyboard shortcut *Ctrl+Shift+Enter*.

### Questions or suggestions

Please contact: M.Sc. Maria Alejandra Vela Castillo | maria_alejandra.vela_castillo1@mailbox.tu-dresden.de
