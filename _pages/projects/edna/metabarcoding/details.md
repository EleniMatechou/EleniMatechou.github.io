---
title: "Metabarcoding – Details"
permalink: /projects/edna/metabarcoding/details/
layout: single
author_profile: true
---

The latest version of the paper can be found on arxiv:

### [eDNAPlus: A unifying modelling framework for DNA-based biodiversity monitoring](https://arxiv.org/abs/2211.12213)

The model uses as input the *reads* for each species, i.e. the count data indicating the number of times the DNA of each species has been read at a given PCR for a given sample.

It is a hierarchical model, which accounts for variation, error and noise in the three levels of metabarcoding surveys:

- **biomass availability**: the amount of biomass for each species available for collection at each surveyed site  
- **biomass collection**: the amount of biomass for each species collected in each physical sample from each surveyed site  
- **biomass analysis**: the amount of biomass detected for each species and physical sample at each PCR run  

Data are only available from the biomass analysis stage (reads), whereas the other two stages are latent. Each stage is modelled using regression-type models with fixed and random effects.

At the **biomass availability** stage, the model accounts for variation between sites due to environmental covariates and species associations, plus random site-level noise.

At the **biomass collection** stage, the model accounts for variation between samples due to sampling effort and species-specific detection effects, plus contamination and failure to collect biomass.

At the **biomass analysis** stage, the model accounts for species-specific PCR efficiency, PCR-to-PCR variation, and false positive/false negative errors.

The model also accounts for spike-ins (addition of known biomass of an external species) to quantify PCR noise.

---

![Model diagram](http://blogs.kent.ac.uk/edna/files/2022/05/Screenshot-2022-05-23-09.22.54.png)

![PCR process](http://blogs.kent.ac.uk/edna/files/2022/05/Screenshot-2022-05-23-09.24.47.png)

![Spike-in diagram](http://blogs.kent.ac.uk/edna/files/2022/05/errors.png)
