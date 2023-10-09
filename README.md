# GDC-Methylation-Data-Pipeline
Comprehensive DNA Methylation Data Processing for All TCGA Cancer Projects

This repository offers a script designed for the comprehensive extraction, processing, and saving of DNA methylation data from The Cancer Genome Atlas (TCGA) projects across all available cancer types.

Table of Contents:
Description
Dependencies
Usage
Output
Contribution
License
Description
The script facilitates seamless data extraction and preparation from the TCGA. The functionalities included are:

Library installation
Data querying based on user-specified project details
Random sample selection
Data download and conversion
Label assignment
Data combination and transposition
CSV output generation
Dependencies
Ensure R is installed with the subsequent packages:

BiocManager
TCGAbiolinks
tidyverse
SummarizedExperiment
sesameData
sesame
The script will handle the installation of these packages if not already present.
