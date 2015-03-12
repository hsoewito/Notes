# This file contains notes for R Commands
## Install packages from CRAN - over 5200 packages
* a <- available.packages()
* head(rownames(a), 3) ## show the names of the first few packages
* install.packages("slidify")
* install.packages(c("slidify","ggplot2","devtools"))

## install packages from Bioconductor
* source("http://bioconductor.org/bioLite.R")
* biocLite() ## install basic version of Bioconductor
* biocLite(c("GenomicFeatures","AnnotationDbi"))

## Loading R Packages
* library(ggplot2) ## no quotes for package name
* search() ## functions list

