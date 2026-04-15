---
title: "Metabarcoding – Download"
permalink: /projects/edna/metabarcoding/download/
layout: single
author_profile: true
---

## R and RStudio setup

To access the eDNAPlus package, install R and RStudio:

- [Download R (Windows)](https://cran.r-project.org/bin/windows/base/)
- [Download R (Mac)](https://cran.r-project.org/bin/macosx/)
- [Download RStudio (Windows)](https://download1.rstudio.org/desktop/windows/RStudio-2022.02.3-492.exe)
- [Download RStudio (Mac)](https://download1.rstudio.org/desktop/macos/RStudio-2022.02.3-492.dmg)

---

## Update R (Windows only)

```r
install.packages("installr")
library(installr)
updateR()

## Install eDNA+ (Windows only)

install.packages("devtools")
library(devtools)
install_github("alexdiana1992/eDNAPlus")
library(eDNAPlus)

Notes
If package dependencies fail, install missing packages with install.packages()
If R crashes during MCMC, restart and retry
If errors occur with quotes, retype quotation marks manually
