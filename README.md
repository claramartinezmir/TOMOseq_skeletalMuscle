# Skeletal muscle spatial transcriptomics analysis

This repository contains the collection of scripts and python notebooks used to perform the transcriptomics analysis presented in [C. Martinez Mir et al](). 

### Summary of the data

* 4 tomo-seq replicates of tibialis anterior muscles

All tomo-seq RNA-seq datasets can be found in the Gene Expression Omnibus (GEO) under accession code [GSE253441](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE253441)


### Organization of notebooks in this repository subfolder

The folder contains python notebooks used to filter and normalized the pre-processed sequencing data. Additionally, python notebooks containing correlation between replicates and differential gene expression analysis are provided. For the notebooks to work, input datasets are required (most of them found [here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE253441); otherwise please contact me. 
The main idea is to select genes with interesting expression patterns along the proximal/distal axis.
