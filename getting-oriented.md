# Getting oriented

In this section, the aim is to have everyone setup with R, RStudio, and RMarkdown.

## Overview

* **Duration** 15 minutes

## Questions

* How do I install R?
* How do I install rmarkdown?
* How do I install LaTeX in a sane way?

## Software Setup

### R

#### Windows

https://cloud.r-project.org/bin/windows/

#### MacOS

https://cloud.r-project.org/bin/macosx/

#### Linux

https://cloud.r-project.org/bin/linux/

### RStudio

https://www.rstudio.com/products/rstudio/download/#download

## RMarkdown


```r
install.packages("rmarkdown", 
                 dependencies = c("Imports", "Suggests"))

install.packages("knitr", 
                 dependencies = c("Imports", "Suggests")) 

install.packages("tinytex",
                 dependencies = c("Imports", "Suggests"))

install.packages('tidyverse')
tinytex::install_tinytex()
```

## Test Script

You should be able to fun the following code on your machine


```r
library(rmarkdown)
library(knitr)
library(tinytex)
library(tidyverse)
```

