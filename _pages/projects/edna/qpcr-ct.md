---
title: "Modelling qPCR Ct values"
permalink: /projects/edna/qpcr-ct/
layout: single
author_profile: true
---

This project was part-funded through an EPSRC PhD studentship.

## Summary

This work developeds a hierarchical modelling framework for qPCR Ct values that allows inference on DNA concentration in the environment, rather than restricting analysis to presence/absence. The model links Ct values to underlying DNA concentration through the full data-generating process, accounting for variation at the stages of DNA availability, sample collection, and laboratory analysis.

A key contribution is the explicit modelling of the relationship between Ct values and DNA concentration while accounting for heteroscedasticity in Ct measurements, variation across PCR runs, and censoring due to failed amplification. The model also incorporates contamination and inhibition within a unified framework, avoiding the need for ad-hoc data filtering or discarding samples.

By propagating uncertainty across all stages, the approach provides more reliable inference on spatial and temporal variation in DNA concentration and the effects of environmental covariates.

## Papers

- [More than presence-absence; modelling (e)DNA concentration across time and space from qPCR survey data](https://doi.org/10.1007/s42519-025-00477-9)

## Code

- [Link to GitHub repo](https://github.com/millyljones/Spatio-temporal-eDNA/tree/main)
