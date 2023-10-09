# GDC-Methylation-Data-Pipeline


# Comprehensive DNA Methylation Data Processing for All TCGA Cancer Projects

## Description
The script facilitates seamless data extraction and preparation from the TCGA. The functionalities included are:
- Library installation
- Data querying based on user-specified project details
- Random sample selection
- Data download and conversion
- Label assignment
- Data combination and transposition
- CSV output generation

## Dependencies
Ensure R is installed with the subsequent packages:
- BiocManager
- TCGAbiolinks
- tidyverse
- SummarizedExperiment
- sesameData
- sesame

The script will handle the installation of these packages if not already present.

## Output
The script will generate a processed data file named `data.csv` in the current directory. This CSV will present the methylation data, with samples as rows and features as columns. An added "Type" column indicates the specific cancer type based on TCGA nomenclature.

## License
This project is licensed under the MIT License. See `LICENSE` for more information.

\end{document}

