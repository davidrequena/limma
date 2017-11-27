## Guide for the Differential Expression Analysis of RNAseq data using limma and voom

Made by David Requena (drequena@rockefeller.edu) and James Saltsman (jsaltsman@rockefeller.edu).

-------------------------------------------------------------------------

This code includes some basic steps:
1. SET UP:
* Install and/or call the required libraries
* Input sample metadata
2. Exploring the data:
* Steps available in my previous guide: https://github.com/SimonLab-RU/DEseq2
3. Data Analysis:
* Prior filtering
* Model matrix
* Comparison
* Annotation and output tables

To run this script, three tables are required:
* A table with the samples' data, containing features of interest (e.g. cases/controls, gender, etc...)
* A table with the gene counts by sample
* A table with genes to be filtered out (e.g. ribosomal genes)
