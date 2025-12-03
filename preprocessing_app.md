---
title: Pre-processing raw data
layout: default
nav_order: 4
---

# What is pre-processing?
Like any assay, the raw data output from a multiplex bead assay will need quality control. There are technical variations in the raw dataset that can be from minor plate to plate variation of MFI values during processing, instrument sensitivity, pipetting errors, or even fluctuations in lab temperatures. Pre-processing is the steps of reducing this variability and transforming the raw multiplex dataset to be usable for downstream analysis. Without pre-processing, the dataset may be biased by confusing technical noise with biological differences. 


# Web application for pre-processing
An R Shiny app was created by the Drakeley group at the London School of Hygeine and Tropical Medicine to standardise the quality control steps of analysing raw multiplex datasets from a Luminex machine.
- If the assay passes the quality control checks, then the data can be cleaned and downloaded for downstream analysis
- no coding is needed
Background and instructions can be found here XXXXX

The app does the following functions:
1. **Bead count**: Visualise wells with low bead counts on each plate. The user can define the bead count threshold, with wells falling below that threshold highlighted in red. If the user does not set a threshold, the default value is 30 beads.
2. **Standard curve**: Plots MFI values against log dilution values. These plots can be used to determine the MFI of a sample at a given dilution. 
3. **Coefficient of variation plots**: Measures the variation between samples in a plate. Calculated as the standard deviation of the sample in each well by the mean.
4. **Levey-Jennings plots**: Tracks how control samples behave over time across plates.
5. **Normalisation**: Seeks differences between units or batches.
6. **Loess**: Visualise the difference between the reference raw data and the normalised plate.
7. **Download**: After quality control (QC) steps, the data can be cleaned by removing samples with low bead count and background MFI either through subtraction or division. The data can then be downloaded in an easily interpretable format for downstream analysis.


The app can be accessed here XXXXX
