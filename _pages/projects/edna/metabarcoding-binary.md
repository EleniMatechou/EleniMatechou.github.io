---
title: "Modelling metabarcoding binary data"
permalink: /projects/edna/metabarcoding-binary/
layout: single
author_profile: true
---

This work was funded by Innovate UK through a KTP with NatureMetrics.

## Summary

This work develops statistical models for analysing **metabarcoding data in binary form** (i.e. detection/non-detection based on whether reads are present). The aim is to infer species occurrence while explicitly accounting for the complex sources of error arising from environmental DNA workflows.

The model extends occupancy modelling to eDNA metabarcoding by:
- accounting for both *false negatives and false positives* arising from field sampling and laboratory processes,
- separating ecological signal from observation error across multiple stages of data generation,
- enabling *multi-species inference* from high-dimensional metabarcoding datasets.

A key development is the *OccPlus framework*, which leverages the structure of metabarcoding data to improve estimation of species occurrence and community patterns. It allows reliable large-scale biodiversity inference from noisy detection data and is designed to scale to high-diversity systems.

## Papers

- [High quality, granular, timely, trustworthy and efficient vertebrate species distribution data across a 30,000 km² protected area complex](https://onlinelibrary.wiley.com/doi/epdf/10.1111/ele.70302)

## Code

An R package implementing the OccPlus model is currently under development.


library(occPlus)
