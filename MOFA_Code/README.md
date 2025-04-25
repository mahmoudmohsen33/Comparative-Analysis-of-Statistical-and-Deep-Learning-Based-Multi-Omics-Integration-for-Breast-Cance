# MOFA Code

This folder contains scripts related to **Multi-Omics Factor Analysis (MOFA)**.

##  Files

- **MOFA.R**  
  This script performs dimensionality reduction and integrative analysis across multi-omics datasets (e.g., transcriptomics, epigenomics, microbiomics) using the MOFA2 framework.

## Requirements

Make sure you have the following installed:
- R (version >= 4.0 recommended)
- MOFA2 package
- Additional R packages:  
  - `data.table`
  - `ggplot2`
  - `reticulate`
  - `MOFA2`

You can install MOFA2 in R by running:
```r
if (!requireNamespace("MOFA2", quietly = TRUE)) {
    devtools::install_github("bioFAM/MOFA2")
}
