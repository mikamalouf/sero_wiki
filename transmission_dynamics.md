---
title: Transmission dynamics
layout: default
has_children: true
nav_order: 6
---

## Estimating the transmission dynamics of cross-sectional serological surveys - a practical application

The following section contains the HTML version of an R markdown establishing the transmission dynamics from cross-sectional multiplex dataset from 2 settings:
1. High transmission setting estimating malarial seroprevalence in Uganda
2. Low transmission setting estimating malarial seroprevalence in a malaria-eliminated country in Southeast Asia

These scenarios use different cutoff methods, where the high transmission script uses a finite mixture model and the low transmission uses a negative control value.

Both transmission scripts reads in functions from a separate script to create the finite mixture model, calculate the age-stratified seroprevalence curve, amongst other things. For more information on the functions, please visit the [GitHub.](https://github.com/mikamalouf/seroimmunology-epi_practical/tree/main/functions)