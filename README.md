# Human DCM-time machine unravels cell state changes during primitive gut tube differentiation
Welcome to the GitHub repository for our manuscript **"Human DCM-time machine unravels cell state changes during primitive gut tube differentiation"**, currently available on [bioRxiv](https://www.biorxiv.org/content/10.1101/2025.09.26.678757v1) and under review at *Genome Biology*.

## Data availability
All raw and processed high-throughput sequencing data (MeD-seq, bulk RNA-seq and scRNA-seq) generated in this study have been submitted to the NCBI Gene Expression Omnibus (GEO) under accession number [GSE304237](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE304237).
Moreover, ChiP-seq datasets from GSE158382, GSE220103, GSE145964 and GSE149148 were reanalyzed.

## Code availability
The directory [Notebooks](https://bitbucket.org/beatricetan/hdcm-tm/src/main/Notebooks/) contains all Jupyter Notebooks used for processing MeD-seq, bulk RNA-seq, scRNA-seq and ChIP-seq data and generating the figures included in the manuscript.

## Installing required software
All software dependencies can be installed using *conda* and the provided environment file.
The hDCM-TM.yml file specifies all required dependencies and version numbers. Run the following command in your terminal to create the environment (named hDCM-TM):
```
conda env create -f hDCM-TM.yml
```
The pyUCell package must be installed separately using pip.

## Citation
If you use this code or data, please cite the manuscript and the archived version of this repository:

**van Leeuwen, M. E., Tan, B. F., Wassenaar, E., Sleddens-Linkels, E., Boers, R., Gontan, C., & Gribnau, J. (2025). _Human DCM-time machine unravels cell state changes during primitive gut tube differentiation._ bioRxiv, 2025.09.26.678757. [https://doi.org/10.1101/2025.09.26.678757](https://doi.org/10.1101/2025.09.26.678757)**

[![DOI](https://img.shields.io/badge/DOI-10.1101/2025.09.26.678757-blue)](https://doi.org/10.1101/2025.09.26.678757)
[![DOI](https://zenodo.org/badge/923085316.svg)](https://doi.org/10.5281/zenodo.16760254)
