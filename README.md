# GDC-Methylation-Data-Pipeline


# Comprehensive DNA Methylation Data Processing for All TCGA Cancer Projects



For those wishing to run or edit this script, it's highly recommended to utilize [Google Colab](https://colab.research.google.com/). The motivation for this recommendation is twofold:

1. **Library Dependencies**: Google Colab provides a streamlined environment for managing the necessary R library dependencies without the need for local setup.
   
2. **Data Volume**: The script processes a significant volume of data. Google Colab offers a cloud-based solution, ensuring smooth performance and alleviating the need for local computational resources.


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

