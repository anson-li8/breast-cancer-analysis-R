# Breast Cancer Data Analysis

A [workflowr][] project.

[workflowr]: https://github.com/workflowr/workflowr

# Breast Cancer Clinical Data Analysis

A learning project by a high school student learning R and workflowr.

This project uses real clinical data from The Cancer Genome Atlas (TCGA) 
breast cancer cohort (1,097 patients), sourced from cBioPortal. The goal 
was not to produce novel research findings, but to get hands-on experience 
with the core tools used in computational biology labs:

- **R / tidyverse** — data manipulation with `dplyr`, visualization with `ggplot2`
- **workflowr** — reproducible research project structure
- **Git / GitHub** — version control and publishing

## What the analysis covers
- Filtering patients by AJCC pathological tumor stage
- Counting and ranking histological subtypes
- Converting survival time from months to years
- Visualizing age at diagnosis and stage distribution
- Exploring age vs. survival by cancer subtype

## Data source
TCGA Breast Cancer (BRCA) cohort via [cBioPortal](https://www.cbioportal.org/study/clinicalData?id=brca_tcga)