
# scRNA-seq Analysis of Human Brain Organoids

## Overview

Reproduction of the single-cell RNA sequencing (scRNA-seq) analysis workflow from the publication:

**Functional Neuronal Circuitry and Oscillatory Dynamics in Human Brain Organoids (2022).**

https://doi.org/10.1038/s41467-022-32115-4

## Repository Structure

- `analysis/`: R Markdown source code.
- `docs/`: Rendered html analysis report; [**Open the interactive HTML analysis report**](https://jojo6297.github.io/scrna-brain-organoids/)
- `notes/`: Supporting lecture notes.

## Analysis

The workflow includes quality control, normalization, variable gene selection, PCA, clustering, UMAP dimensionality reduction, doublet detection and marker gene identification.

Main R packages include Seurat and DoubletFinder.

## Reference

Functional Neuronal Circuitry and Oscillatory Dynamics in Human Brain Organoids. Nature Communications (2022).