---
title: "Modelling metabarcoding count data"
permalink: /projects/edna/metabarcoding-counts/
layout: single
author_profile: true
---

This project was funded by NERC (project [NE/T010045/1](https://gtr.ukri.org/projects?ref=NE%2FT010045%2F1)) as part of the [Landscape Decisions](https://landscapedecisions.org/) theme.

It was a collaboration across four universities (University of Kent (Dr Eleni Matechou, Professor Richard Griffiths, Dr Alex Diana as the PDRA), UCL (Professor Jim Griffin), University of East Anglia (Professor Douglas Yu) and Lancaster University (Dr Alex Bush)).

## Summary

This work developed a unified hierarchical model for metabarcoding read count data that links observed reads to underlying species biomass through the full data-generation process. The model explicitly accounts for variation and error at three stages: biomass availability at sites, biomass collection into samples, and laboratory analysis through PCR.

A key contribution is the ability to separate ecological signal (true variation in DNA biomass) from observation processes, including sampling inefficiencies, PCR bias, and both false positive and false negative errors. By modelling these components jointly, the approach allows inference on relative DNA concentration across species and sites, rather than relying on raw read counts.

The framework also incorporates species interactions and experimental features such as spike-ins, providing a principled way to quantify uncertainty and improve comparability across samples and studies.

## Papers

- [eDNAPlus: A unifying modelling framework for DNA-based biodiversity monitoring](https://www.tandfonline.com/doi/full/10.1080/01621459.2024.2412362)

## Code

- [Link to github repo](https://github.com/alexdiana1992/eDNAPlus)
