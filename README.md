# Coho Salmon Projec

Statistical analysis of physiological parameters in Coho Salmon. 

## Overview
This repository contains the Rmd file and analyses for the Coho Salmon Project. The Rmd file contains:
* Data cleaning
* Normality testing (Shapiro-Wilk)
* Outlier elimination (Horn's Algorithm)
* Reference Interval (RI) calculation with 90% bootstrap confidence intervals
* Two-sample t-tests with Benjamini-Hochberg (BH) FDR correction

## Requirements
To run the code for yourself, please make sure you have the following installed:
* [R](https://cran.r-project.org/) (required)
* [RStudio](https://posit.co/download/rstudio-desktop/) (recommended)
* **R Packages**: `readxl`, `boot`, `tinytex` (automatically installed by the `.Rmd` script if missing)

## Contributors & Acknowledgments

Thank you to Gregory Lewbart, Chris Gaudette, and Kelsie Dougherty as the key contributors to this project. 

### Data Source
Special thanks to the **North Carolina State University College of Veterinary Medicine** for providing the data used in this analysis.
