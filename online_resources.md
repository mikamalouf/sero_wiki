---
title: Online resources
layout: default
---

# Seroanalytic online resources

Below are a list of online resources

---
## Websites
[Serosurvey Tools](Serosurveytools.org)   
An online resource developed by Johns Hopkins University and the International Vaccine Access Centre that offers learning modules, tools, and guidance for designing and conducting a serosurvey.  

[SeroTracker](https://www.serotracker.com/)  
Source for COVID-19, MERS, and Arbovirus Seroprevalence Data.  

[Seroanalytics Hub](https://www.iddynamics.jhsph.edu/seroanalytics-hub)  
Research group based at Johns Hopkins University aiming to create an online wiki for seroanalytics.  

[Seroanalytics](https://seroanalytics.org/)
Many R packages below can also be found on the Seroanalytics website. This website is a free and open source directory of tools for analysing serological data.

[SeroViz](https://seroanalytics.org/seroviz-web/)
A web application for visualising surveillance and post-exposure data. The GitHub can be accessed [here](https://github.com/seroanalytics/seroviz). Please note that the saved link to access the web application on the GitHub is incorrect. Please use the link on this page to access the app.

---
## Tutorials
[seroepirecipes](https://github.com/seroanalytics/seroepirecipes)
A codebase of tutorials and the implementation of common seroanalytical models. The code was created by the seroanalytics GitHubThis codebase accompanies a [literature review of serodynamics](https://www.sciencedirect.com/science/article/pii/S1755436524000677).

---

## R packages

#### Pre-processing/Quality control
BREAD  
Pre-processing code developed by the Johns Hopkins group
XXXX MIKA NOTE: FIND CODE OR INFO XXXXX

[SerolyzeR](https://github.com/mini-pw/SerolyzeR)  
R package to pre-processing raw data to an analysable form.

[shinyMBA](https://github.com/CDCgov/shinyMBA)  
R shiny application developed by the US CDC to streamline quality control (QC) analyses for serosurveillance studies using the Luminex multiplex bead assay (MBA). You can read more on its use and development [here](https://www.nature.com/articles/s41598-024-57652-4#Ack1)


#### Estimating the transmission dynamics 
[Rsero](https://github.com/nathoze/Rsero)  
R package to estimate the annual force of infection using cross-sectional serological data.
More information on its development and application is described in their [2025 publication](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012777)

[Serocalculator](https://github.com/UCD-SERG/serocalculator)  
An R package designed to estimate sero-incidence from cross-sectional data. Modelled from longitudinal data.  

[seroFOI](https://github.com/epiverse-trace/serofoi )
R package that estimates the Force-of-Infection of a given pathogen from population-based, cross-sectional sero-prevalence studies

[serojump](https://github.com/seroanalytics/serojump )
R package provides tools for fitting longitudinal serological models to antibody kinetics data using reversible-jump Markov Chain Monte Carlo (RJ-MCMC). You can read more on its implementation [here](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1013467)

[serosolver](https://github.com/seroanalytics/serosolver)  
R package developed to create an inference framework for longitudinal serological data.  


#### Generate synthetic data
[Seroism](https://github.com/seroanalytics/serosim)  
R package for simulating serosurvey data using custom models for the data-generating process. Generates data for testing and validation.
More information can be found in their [publication](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011384).  


## Other
[MultiSero](https://github.com/meganodris/MultiSero)  
R code to to dis-entangle cross-reactivity. The preprint describing its use and development can be found [here](https://www.medrxiv.org/content/10.1101/2024.08.12.24311852v1).

[enterics-seroepi](https://github.com/ben-arnold/enterics-seroepi)
GitHub storing data and computational notebooks to support a [paper on enteropathogen antibody dynamics in children from low-resource settings](https://elifesciences.org/articles/45594#content).

