---
title: "Modelling binary qPCR data"
permalink: /projects/edna/qpcr-binary/
layout: single
author_profile: true
---

This project was part-funded by NERC (project [NE/T010045/1](https://gtr.ukri.org/projects?ref=NE%2FT010045%2F1)) as part of the [Landscape Decisions](https://landscapedecisions.org/) theme.

## Summary

This work developeds hierarchical occupancy models for qPCR detection/non-detection data that explicitly account for imperfect observation in DNA-based surveys. The models separate the ecological process of species presence from the observation process, allowing for both false negative errors (failure to detect DNA when present) and false positive errors (detection due to contamination or other sources).

A key contribution is the formulation of a two-stage observation model that distinguishes between errors arising during sample collection and those arising during laboratory analysis. This framework allows the use of replicate qPCR measurements to quantify detection probabilities and error rates, rather than relying on arbitrary thresholds for declaring presence.

The approach also incorporates environmental covariates and Bayesian variable selection to identify drivers of species occurrence, and provides a principled basis for estimating occupancy at large spatial scales. Subsequent work extends the framework to improve survey design, assess reliability of national-scale monitoring programmes, and provide accessible implementation through an RShiny application.

## Papers

- [Modelling environmental DNA data; Bayesian variable selection accounting for false positive and false negative errors](https://academic.oup.com/jrsssc/article/69/2/377/7058533?guestAccessKey=)

- [Optimising sampling and analysis protocols in environmental DNA studies](https://www.nature.com/articles/s41598-021-91166-7)

- [An RShiny app for modelling environmental DNA data: accounting for false positive and false negative observation error](https://nsojournals.onlinelibrary.wiley.com/doi/full/10.1111/ecog.05718)

- [Reliability of environmental DNA surveys to detect pond occupancy by newts at a national scale](https://www.nature.com/articles/s41598-022-05442-1)

## Code

- [Link to RShiny app](https://seak.shinyapps.io/eDNA/)
